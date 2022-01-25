# Irassochio001
Cadastro de produtos de atacado com categoria e valores .
produtos  =  [ 'caixa pizza','queijo','massa pizza','molho','calabresa','cebola','azeitona','frango','requeijão','milho' ] 
valores  =  [ 2.99,49.90,2.00,2.00,24.90,5.00,15.00,13.49,25.00,3.00 ] 
Categorias  =  [ 'embalagens','insumos' ]

#perguntar nome completo do cliente e cpf com input

cliente = input('Olá, seja bem vindo!Digite seu nome completo ')
cpf_cliente = input('Digite seu cpf ')
print(cliente,
      
      cpf_cliente
     )

#digitei o produto que deseja colocar no carrinho

produto = input('Digite seu produto ')
for i,produto in enumerate(produtos):
    print(i)
