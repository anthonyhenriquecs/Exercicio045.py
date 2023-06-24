# Exercicio045.py


from random import randint
itens = ('pedra','papel', 'tesoura')
comp: int = randint(0,2)
print('''Suas opções
[ 0 ]pedra
[ 1 ]papel
[ 2 ]tesoura
''')

jogador = int(input('Qual sua jogada: '))
print('O computador escolheu {} '.format(itens[comp]))
print('O jogador escolheu {} '.format(itens[jogador]))
