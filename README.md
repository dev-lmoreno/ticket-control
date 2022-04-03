### Sistema de Cadastro e Priorização de Tickets
#### Funcionalidades - V1 [ ]
- Ao acessar a plataforma deve-se listar todos os tickets já salvos do sistema (tickets.json) em uma tabela, possuindo os campos TicketID, CategoryID, CustomerID, CustomerName, CustomerEmail, DateCreate, DateUpdate.

#### Funcionalidades - V2 [ ]
- Adicionar filtro para cada um dos campos da tabela
- Adicionar paginação de registro na tabela (Ex: listar 10 registros por página, listar 25 registros por página)

#### Funcionalidades - V3 [ ]
- Adicione uma nova coluna chamada Detalhes, onde deve conter um botão com o sinal de "+". Ao clicar nesse botão deve ser exibida uma modal listando o TicketID aberto e uma tabela com os campos Subject, Message, DataCreate e Sender e seus respectivos valores para o Ticket que foi aberto

#### Funcionalidades - V4 [ ]
- Adicionar uma nova coluna chamada Priorização, onde nela será exibida a prioridade do Ticket, podendo ser Baixa, Normal ou Alta. (Use seus critérios e sua própria lógica para fazer essa classificação)

#### Funcionalidades - V5 [ ]
- Desenvolver um sistema de Login (Contendo o cadastro do login). Inicialmente será apenas feito o cadastro do usuário e passando as credenciais certas deverá ser redirecionado para a tela de listagem dos Tickets
- Observação: Para este caso pode-se integrar a funcionalidade com banco de dados ou salvar os valores em um novo arquivo json chamado loginControll.json

### Observação
- O arquivo tickets.json está no repositório para que se possa iniciar o desenvolvimento
