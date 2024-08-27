# 2. Requisitos Não Funcionais

<p align="justify">A <i>Tabela 2</i> a seguir contém os <b>Requisitos Não Funcionais (RNF)</b> elicitados utizando a técnica de Brainstorm .</p>

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

<div style="text-align: center">
<p>Tabela 2: Requisitos Não Funcionais</p>
</div>
