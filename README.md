# Projeto GarageCode
## Integrantes do grupo
-> André Rocha (andre2105@gmail.com)
## Descrição geral do projeto 
Esta aplicação destina-se à auxiliar os funcionários de uma oficina mecânica no gerenciamento e operação do seu dia-a-dia, abrangendo toda a parte de administração do empreendimento, como gerenciamento de caixa, recursos humanos e estoque de produtos, assim como a parte operacional, como emissão de ordens de serviço, acompanhamento do progresso do serviço e vendas de produtos.
Principais funcionalidades:
 - Gerenciar estoque de produtos, registrando sua saída nas operações de venda, emitindo aviso à administração quando houver baixa quantidade de algum produto, e admitindo a entrada de produtos no estoque mediante usuário autorizado;
- Gerenciar o quadro de funcionários da empresa, contendo as informações sobre cada funcionário (nome, cargo, salário…), e permitindo ao usuário autorizado o cadastro e desligamento de funcionários.
- Permitir a criação e a manipulação de um cadastro de clientes pelo usuário autorizado.
- Auxiliar no processo de venda de produtos e serviços, gerando orçamentos baseado na necessidade de cada cliente, e emitindo ordens de serviço.
## Lista de requisitos do projeto
1. Acesso ao sistema através de login e senha. Níveis de acesso baseado em hierarquia de usuários (administração, atendimento, oficina).
2. O sistema deve permitir o gerenciamento (Create, Recover, Update e Delete - CRUD) de clientes e essa ação pode ser feita por usuários com nível de atendimento ou administração.
3. O sistema deve permitir o gerenciamento (CRUD) de funcionários e estoque da oficina, e essa ação somente pode ser executada por usuários do nível administração. Usuários administradores também podem executar todas as funcionalidades que um atendente pode executar.
4. Atendimento pode abrir um orçamento de venda.
5. Oficina pode executar e finalizar uma ordem de serviço.
6. Administração pode autorizar orçamentos de compra e venda, movimentar estoque, suspender ordens de serviço, acessar relatórios.
7. Orçamento autorizado cria uma ordem de serviço.
8. Orçamento e movimentação no estoque alteram o balanço.
9. O balanço pode gerar relatórios.
10. Estoque pode encaminhar um orçamento de compra ao administrador, de acordo com o nível do estoque de cada produto.
