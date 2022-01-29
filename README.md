# Irassochio001
produtos  =  [ 'caixa pizza','queijo','massa pizza','molho','calabresa','cebola','azeitona','frango','requeijão','milho'] 
valores  =  [ 2.99,49.90,2.00,2.00,24.90,5.00,15.00,13.49,25.00,3.00] 

#perguntar nome completo do cliente e cpf com input

cliente = input('Olá, seja bem vindo!Digite seu nome completo ')
cpf_cliente = input('Digite seu cpf ')
print(cliente,
      
      cpf_cliente
     )
#lista com produtos digitados
carrinho_produtos = []
valores_produtos = []

#digitei o produto que deseja colocar no carrinho
while True:
    produto = input('Digite o produto:     ')
    carrinho_produtos.append(produto)
    if produto == '':
        print('Pedido finalizado!Suas compras foram {}'.format(carrinho_produtos))
        break  
    i = produtos.index(produto)
    valores_produtos.append(valores[i])
    print(valores_produtos)
soma_dos_produtos  = 0  
for valores in valores_produtos:
    soma_dos_produtos += valores
texto = ('Total a pagar R$:{}'.format(soma_dos_produtos))
print(texto)
