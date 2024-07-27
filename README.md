# O Mistério do Relógio Quebrado

#Apresentação
print('Olá detetive, meu nome Sheldon estava aguardando a sua chegada.')
nome = input ('Diga o seu nome para Sheldon: \n')
print('Sheldon: Parece que a viagem foi bem longa para chegar até aqui,\n' 'Deixe-me atualiza-lo sobre o caso, antes que fique tarde de mais. \n')

#Descrição


print(' ')
print('Descrição do crime \n')

print(' Na manhã de um sábado ensolarado, o nomeado relojoeiro Sr. Alberto Silva foi encontrado morto em sua loja, a "Casa dos relógios", localizada no centro da cidade. \
A cena do crime revelou um cenário curioso: \n'
'  \n'
'1. O Sr. Alberto foi encontrado caído ao lado de um relógio antigo, que \n' 'parecia ter sido danificado. \n' 
'  \n'
'2. A loja estava trancada por dentro, e não havia sinais de arrombamento.\n'
'  \n'
'3. O dinheiro no caixa estava intacto. \n'
'   \n'
'4. O relógio quebrado estava em cima de uma mesa de trabalho, e parecia ter \n' 'marcas de ferramentas.')
print('')
#Suspeito
print('Suspeitos \n')

print('1. Ana, a assistente do Sr. Alberto, que tinha um histórico de desentendimentos com ele sobre a direção dos negócios \n'
' \n' 
'2. Carlo, um cliente regular que tinha recentemente pedido uma grande quantidade de conserto de relógios e estava insatisfeito com o prazo \n' 
' \n'
'3. Joana, a ex-esposa do Sr. Alberto, com quem ele estava em um processo de divórcio complicado. \n' 
' \n '
'4. Pedro, um colega relojoeiro que havia tido uma discussão pública com Alberto sobre um segredo de relojoaria'
' \n ')

#Pistas
print('Suspeitos \n')

print('1. Uma chave inglesa: foi encontrada perto do relógio quebrado. \n'
'\n '
'2. Um bilhete amassado: foi encontrado no bolso do Sr. Alberto, com a mensagem: "Desculpe, não consegui consertar a tempo" \n'
'\n'
'3. Um livro de contas: estava aberto na página com anotações sobre a conta de Carlos.')

#Análise

print('Sheldon: Por enquanto é toda pista que temos, Boa Sorte contamos com o senhor')

#Código
print('')
suspeito = input('Quem assasinou o se Sr.Alberto? \n').capitalize()
print('')
if suspeito == 'Carlos':
    print('Sheldon: Parabéns você solucionou o caso e conseguiu prender o suspeito')
    print('Sheldon: Você é um ótimo detetive, agora precisamos de você em outro caso')
    print(f' Sheldon: Foi um enorme prazer em trabalhar com você Sr {nome}.')
else:
    print('Sheldon: Você prendeu a pessoa errada e o suspeito acabou descobrindo e fugiu  para longe')
    print('Sheldon: Não se preocuope com a fulga dele, pois o mesmo deixou o monte de pista')
    print('Sheldon: Irei junta-las para você e logo lhe darei uma posição')
