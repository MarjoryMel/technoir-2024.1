# 1. História de Usuário

A Tabela 3 a seguir contém as Histórias de Usuárias elicitadas.

<table>
    <thead>
        <tr style="background-color: purple; color: white">
            <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
            <th style="border-style:solid;border-width:1px;text-align:center">História de Usuário</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Critérios de aceitação</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
            <th style="border-style:solid;border-width:1px;text-align:center">RF/RNF relacionado</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como usuário, desejo visualizar as promoções de jogos para aproveitar ofertas e jogos gratuitos.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">
                <ol>
                    <li>Ao acessar o site, as promoções de jogos devem ser exibidas de forma clara e destacada na página inicial.</li>
                    <li>Cada promoção deve incluir informações detalhadas sobre o jogo em oferta, como título, descrição e plataforma disponível.</li>
                    <li>O usuário deve ser redirecionado para a biblioteca de jogos ao clicar em um jogo listado.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF02, RF03, RF15</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como um novo usuário da plataforma, eu quero ser capaz de criar meu próprio perfil para personalizar minha experiência e gerenciar minhas preferências.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">
                <ol>
                    <li>O formulário de registro deve incluir campos para nome, sobrenome, e-mail e senha.</li>
                    <li>Todos os campos obrigatórios devem ser preenchidos para criar o perfil.</li>
                    <li>As senhas devem atender aos requisitos mínimos de segurança.</li>
                    <li>O sistema deve salvar todas as informações do perfil do usuário em um banco de dados seguro.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01, RF07</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como um usuário registrado, desejo poder gerenciar meu perfil e manter minha conta atualizada.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">
                <ol>
                    <li>Devo ser capaz de acessar uma página de perfil onde possa visualizar e editar minhas informações pessoais.</li>
                    <li>Todas as alterações feitas no perfil devem ser salvas corretamente e refletidas na minha experiência no site.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01, RF05</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como um usuário, desejo acessar informações detalhadas sobre os jogos em promoção ou gratuitos.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">
                <ol>
                    <li>Cada jogo listado deve incluir informações como título, descrição, plataformas suportadas e data de término da promoção.</li>
                    <li>Deve haver um botão para adicionar o jogo aos favoritos diretamente na página de detalhes.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF03, RF14</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como um usuário, desejo receber notificações sobre novas promoções de jogos para que eu possa aproveitar as melhores ofertas a tempo.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">
                <ol>
                    <li>O usuário deve poder habilitar/desabilitar as notificações na página de perfil.</li>
                    <li>As notificações devem ser enviadas pelas opções escolhidas pelo usuário ou aparecer na plataforma, conforme as preferências definidas pelo usuário.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF04, RF13</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como um usuário, desejo entrar em contato com os administradores do site para enviar feedback ou solicitar suporte.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">
                <ol>
                    <li>O formulário de contato deve estar acessível na página de Contato e deve permitir o envio de nome, e-mail e mensagem.</li>
                    <li>O sistema deve confirmar o envio bem-sucedido da mensagem ao usuário.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF08, RF09</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US07</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como um usuário, desejo buscar jogos específicos para ver se estão em promoção ou gratuitos.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">
                <ol>
                    <li>A barra de pesquisa deve estar visível em todas as páginas do site.</li>
                    <li>O usuário deve poder buscar pelo nome do jogo e ver os resultados correspondentes.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF16</td>
        </tr>
    </tbody>
</table>

<div style="color:purple; font-weight:bold;">Tabela 3: Histórias de Usuário</div>
