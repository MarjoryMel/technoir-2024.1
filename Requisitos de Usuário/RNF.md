# 2. Requisitos Não Funcionais

<p align="justify">A <i>Tabela 2</i> a seguir contém os Requisitos Não Funcionais (RNF): </p>

| ID   |                                 Requisito NF                              | Categoria/Tipo | Prioridade | Requisitos Relacionados |
| :--: | :-----------------------------------------------------------------------: |:-------------: | :--------: | :-----------------: |
| RNF01 |  O site deve ser compatível com os navegadores web: Chrome, Firefox, Opera e Edge.               |   Produto/Portabilidade      |    Alta        |        -             |
| RNF02 | O site deve ser acessível de forma consistente em diferentes navegadores, como o Google Chrome, Brave e Opera GX. | Produto/Compatibilidade | Alta | - |
| RNF03 | O sistema deve armazenar as informações dos usuários em conformidade com a Lei Geral de Proteção de Dados (Lei nº 13.709/2018)|  Externos/Legais      |    Alta     |      -     |
| RNF04 | O sistema não deve revelar aos operadores nenhuma informação pessoal dos usuários.| Externos/Éticos | Alta |      -     |
| RNF05 | O site deve carregar em até 3 segundos em conexões de banda larga. | Produto/Desempenho | Média | - |
| RNF06 | O site deve ser responsivo, adaptando-se automaticamente a diferentes tamanhos de tela, como desktops, tablets e smartphones. | Produto/Usabilidade | Alta | - |
| RNF07 | O sistema deve ser capaz de suportar até 10.000 usuários simultâneos sem degradação do desempenho. | Produto/Desempenho | Alta | - |
| RNF08 | O site deve manter uma disponibilidade mínima de 99,5%, garantindo alta disponibilidade aos usuários. | Produto/Confiabilidade | Alta | - |
| RNF09 | As notificações enviadas pelo sistema devem ser entregues aos usuários em até 1 minuto após o disparo. | Produto/Desempenho | Média | - |
| RNF10 | O sistema deve garantir a segurança das transações realizadas pelos usuários, incluindo criptografia de dados sensíveis como informações de pagamento. | Produto/Segurança | Alta | RNF03 |
| RNF11 | O sistema deve ser capaz de realizar backups automáticos dos dados do usuário a cada 24 horas para garantir a recuperação em caso de falhas. | Produto/Confiabilidade | Média | RNF03 |
| RNF12 | O sistema deve ser escalável para permitir a adição de novos servidores sem interrupção do serviço, garantindo a capacidade de crescimento do número de usuários. | Produto/Escalabilidade  | Alta  | RNF03, RNF10 |
| RNF13 | O sistema deve suportar escalabilidade horizontal, permitindo a adição de mais servidores para lidar com o aumento de tráfego sem comprometer o desempenho. | Produto/Desempenho | Alta | RNF07, RNF08 |
| RNF14 | O sistema deve ser auditável, mantendo logs detalhados de todas as transações e atividades do usuário, que devem ser armazenados por no mínimo 6 meses. | Produto/Segurança | Média | RNF03, RNF10 |
| RNF15 | O sistema deve ser projetado para minimizar o consumo de recursos no servidor, utilizando técnicas de otimização como cache de dados e compactação de arquivos estáticos. | Produto/Desempenho | Média | RNF07, RNF13|
| RNF16 | O sistema deve ter um mecanismo para expiração e gerenciamento de sessões de usuário para manter a segurança.| Produto/Segurança | Alta | RNF10|
| RNF17 | O sistema deve realizar validações de entrada rigorosas para garantir a integridade e a segurança dos dados do usuário.| Produto/Segurança | Alta | RNF19|
| RNF18 | O sistema deve suportar a sincronização de dados em tempo real para aplicações que exigem atualizações instantâneas, como notificações e interações ao vivo.| Produto/Desempenho | Alta | RNF09|
| RNF19 | A aplicação deve oferecer uma experiência de usuário consistente em todos os dispositivos, independentemente de plataforma (desktop, tablet, smartphone).| Produto/Usabilidade | Alta | RNF06|
| RNF20 | O sistema deve permitir que os usuários reportem bugs e problemas diretamente através de um formulário de feedback integrado na página de contato.| Produto/Usabilidade | Média | - |
| RNF21 | O sistema deve implementar um controle rigoroso de acesso baseado em funções para garantir que apenas usuários autorizados possam acessar áreas e funcionalidades específicas.| Produto/Segurança | Alta | RNF10 |

<div style="text-align: center">
<p>Tabela 2: Requisitos Não Funcionais</p>
</div>
