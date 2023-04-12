### Stock Shop Stystem
- O objeto principal desse projeto é aplicar os conhecimentos basícos no desenvolviment de uma api rest usando springboot.
- The main object of this project is apply the basic learned knowlegde of development the api rest using springboot. 

##### Histórias do Sistema.
- The system must allow the user could manager the actions of your store on geral vision, products, users, sales, reports.
- O sistema deve permitir que o usuário possa ser capaz de gerenciar as atividades da sua loja para os fluxos de visão geral, produtos, usuários, vendas e relatórios.


###### Histórias da Visão Geral

[] - O sistema deve contém um dashboard permitindo que o usuário possa ser capaz de ter uma visão macro de todas as funcionalidades do sistema.
[] - O sistem deve ser capaz de mostrar o total de usuários cadastrados.
[] - O sistema deve ser capaz de mostrar o total de produtos cadastrados.
[] - O sistema deve ser capaz de mostrar o tal de vendas cadastradas.
[] - O sistema deve possuir um gráfico  trazendo um balanço diário. (Opcional)
[] - O sistema deve possuir um gráfico trazendo o balanço semanal. (Opcional)
[] - O sistem deve possuir um gráfíco trazendo o balanço anual.

##### Histórias de Produto

- O sistema deve permitir que o usuário consiga gerenciar as atividades relacionadas ao produto.Nesse primeiro momento o produto deverá conter os seguintes campos( código, SKU, Nome, e Preço, Status(Disponível, Indisponivel, Data de criação.)).

[] - O sistema deve exibir um tabela contendo todas as informações dos produtos
[] - O sistema deve permitir que a tabela exiba de 10 em 10 produtos por demanda.
[] - O sistema deve permitir que o usuário possa excluir um produto.
[] - O sistema deve permitir que o usuário possa editar um produto.
[] - O sistem deve permitir que o usuário filtre as registros por status.
[] - O sistema deve permitir que o usuário filtre os registros por pelo nome.
[] - O sistema deve permitir que a  tabela ordene os elementos com base na coluna.
[] - O sistema deve permitir que o usuário possa extrair os registros em excel.


##### Histórias Cadastro Produto e Edição de Produto

O sistema deve permitir que o usuário consiga cadastrar novos produtos no sistema, para se cadastrar um novo produto o usuário deve preencher 
* SKU, * Nome, * Preço, * Descrição, * Status, * Data de criação.
[] - O sistema não deve permitir cadastrar SKU repetidos.
[] - O sistema deve exibir uma mensagem que o já possui um registro cadastradado com a aquele campo cadastrado.(SKU, nome).
[] - O sistema não deve permitir cadastrar nome repetidos.
[] - Ao salvar um registro o sistema deve exibir um mensagem de sucesso.
[] - O sistema não deve permitir que o usuário edite o SKU
[] - O sistema deve permitir que no momento que o registro seja criado ele comece inativo.

##### Histórias Cliente 

- O sistema deve permitir que o usuário consiga gerenciar as ativades relacionadas ao cliente.
Informações do cliente (Id, Nome, CPF, Email, Telefone, Status(ativo, inativo))
[] - O sistema deve exibir um tabela contendo todas as informações dos usuários
[] - O sistema deve permitir que a tabela exiba de 10 em 10 usuários por demanda.
[] - O sistema deve permitir que o usuário consiga filtrar os registros por status e busca
[] - O sistema deve permitir que o usuário possa excluir um cliente.
[] - O sistema deve permitir que o usuário possa editar um cliente.
[] - O sistem deve permitir que o usuário filtre as registros por status.
[] - O sistema deve permitir que o usuário filtre os registros por pelo nome.
[] - O sistema deve permitir que a  tabela ordene os elementos com base na coluna.
[] - O sistema deve permitir que o usuário possa extrair os registros em excel.


##### Histórias Cadastro e Edição de Cliente 

O sistema deve permitir que o usuário consiga cadastrar novos produtos no sistema, para se cadastrar um novo produto o usuário deve preencher 
* Nome, *CPF, *Nascimento * Endereço, *Email, *Telefone

[] - O sistema não deve permitir que o cliente possua o mesmo cpf.
[] - O sistema não deve permitir que o cliente possua o mesmo email.
[] - Ao salvar um registro o sistema deve exibir um mensagem de sucesso.
[] - Ao editar um cliente o campo de cpf precisa ficar desabilitado.

#### Histórias para Criar uma venda 
O sistema deve permitir que o usuário consiga criar uma venda(campos necessário para realizar a venda) 
* Cliente, * Código do produto, * Quantidade 

[] - O sistema deve adicionar uma lista de compras conforme o usuário seleciona os itens.
[] - A lista deve contém Código, SKU, Produto, Preço Unitário, QTD, Total.
[] - Caso a lista esteja vazia o sistema deve mostrar uma mensagem a lista está vazia.
[] - O Sistema deve informar a forma de Pagamento(Dinheiro, Pix, Cartão).
[] - O Sistema deve informar a quantidade de parcelas
[] - O Sistema deve realizar o calcúlo do total.

### Histórias do Relatório de Vendas
O sistema deve permitir que o usuário consiga gerar relatórios de vendas.
Campos para filtragem são opcionais ( Nome/ Código/ Data Inicio/ Data Fim)
[] - Caso o usuário preencha algum dos campos o relatório devera ser filtrado.
[] - Caso o não algum dos campos o sistema deve gerar todos os relatórios.