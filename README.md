Executando Operações em Python

1) [+] (adição)
2) [-] (subtração)
3) / (divisão)
4) // (divisão inteira)
5) [*] (multiplicação)
6) ** (potênciação)

OBS: NÃO LEVAR EM CONSIDERÇO OS []

EXERCÍCIO

Faça um Programa que pergunte em que turno você estuda. Peça para digitar M-matutino ou V-Vespertino ou N- Noturno. Imprima a mensagem "Bom Dia!", "Boa Tarde!" ou "Boa Noite!" ou "Valor Inválido!", conforme o caso.

RESOLUÇÃO:


a=str(input('Qual o turno: '))
if a=='m' or a=='M':
	print('Bom dia')
elif a=='v' or a=='V':
	print('Boa tarde')
elif a=='n' or a=='N':
	print('Boa noite')
else:
	print('argumento invalido')
