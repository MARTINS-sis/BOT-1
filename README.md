serviços = input('Digite 1 para Pagamento\nDigite 2 para Visualizar Fatura\nDigite 3 para Segunda Via da Fatura\nDigite 4 Para Falar com Atendente\nDigite sua escolha: ')
if serviços == "1":
                 print('Pagamento na Chave Pix: 000')
elif serviços == '2':
                 print('Informe o Nome do Cliente')
                 input('Digite o nome do Cliente')
                 print('Aqui está sua Fatura')
elif serviços == '3':
                 print('Informe o Nome do Cliente')
                 input('Digite o nome do Cliente')
                 print('Aqui está a Segunda Via da sua Fatura')
elif serviços == '4':
                 print('Estamos te Redirecionando a um dos nossos Atendentes')
else:
                 print('Erro')
