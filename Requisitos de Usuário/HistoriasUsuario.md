
# 1. História de Usuário

A Tabela 3 a seguir contém as Histórias de Usuárias elicitadas. 

<table>
    <thead>
        <tr style="background-color: purple; color: white" >
            <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
            <th style="border-style:solid;border-width:1px;text-align:center">História de Usuário</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Critérios de aceitação</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
            <th style="border-style:solid;border-width:1px;text-align:center">RF/RNF relacionado</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como usuário, desejo visualizar as promoções de jogos para aproveitar ofertas e novidades.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">
                <ol>
                    <li>Ao acessar o site, as promoções de jogos devem ser exibidas de forma clara e destacada na página inicial.</li>
                    <li> Cada promoção deve incluir informações detalhadas sobre o jogo em oferta, como título, descrição e preço. </li>
                </ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF03</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como um novo usuário da plataforma, eu quero ser capaz de criar meu próprio perfil, garantindo que todas as informações fornecidas sejam salvas corretamente para uso futuro na aplicação.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">
                <ol>
                    <li>O formulário de registro deve incluir campos para nome, sobrenome, e-mail e senha.</li>
                    <li>Todos os campos obrigatórios devem ser preenchidos para criar o perfil.</li>
                    <li>As senhas devem atender aos requisitos mínimos de segurança, como ter no mínimo oito caracteres e incluir pelo menos uma letra maiúscula, uma letra minúscula, um número e um caractere especial.</li>
                    <li>Após o registro bem-sucedido, o sistema deve salvar todas as informações do perfil do usuário em um banco de dados seguro.</li>
                    <li>O usuário só deve conseguir acessar sua conta após a ativação bem-sucedida por meio do link enviado por e-mail.</li>
                </ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como um usuário registrado, desejo poder gerenciar meu perfil na plataforma e escolher minhas preferências de jogos, para que eu possa personalizar minha experiência de acordo com meus interesses e receber recomendações relevantes.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol>
                <li>Devo ser capaz de acessar uma página de perfil onde possa visualizar e editar minhas informações pessoais, como nome, sobrenome, e-mail, senha, etc.</li>
               <li>Devo ser capaz de alterar qualquer informação do meu perfil, exceto o e-mail, que é usado como identificador único.</li>
                <li>Devo ser capaz de visualizar e editar minhas preferências de jogos, incluindo gêneros preferidos, plataformas de jogo (PC, console, mobile), jogos favoritos, etc.</li>
                <li>Devo ser capaz de receber recomendações personalizadas com base nas minhas preferências de jogos.</li>
                <li>Todas as alterações feitas no perfil e nas preferências de jogos devem ser salvas corretamente e refletidas em todas as áreas relevantes da plataforma.</li> 
            </ol></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF03</td>
        </tr>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Como um usuário desejo acessar informações detalhadas sobre os jogos disponíveis na plataforma, para que eu possa tomar decisões antes de fazer uma compra ou jogar um título.</td>
           <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><ol>
                    <li>Deve haver uma seção ou página dedicada no site onde os jogos são listados.</li>
                    <li>Cada jogo listado deve incluir informações como título, descrição, gênero, plataformas suportadas, data de lançamento e preço.</li>
                    <li>Os jogos devem ser categorizados de forma clara (por gênero, popularidade, data de lançamento, etc.) para facilitar a navegação.</li>
                    <li>Os detalhes do jogo devem ser apresentados de maneira atraente e informativa, com imagens de capa ou trailers disponíveis para uma pré-visualização.</li>
                    <li>Os usuários devem poder clicar em um jogo para obter mais informações detalhadas.</li>
                    <li>Todas as informações sobre os jogos devem ser atualizadas e precisas.</li>
                </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF03</td>
        </tr>
        

</table>

<div style="text-align: center">
<p>Tabela 3: História de Usuário</p>
</div>
