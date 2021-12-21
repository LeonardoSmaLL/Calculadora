# Calculadora
Python
def add(x, y):
    return x + y


def subtracao(x, y):
    return x - y


def multiplicacao(x, y):
    return x * y


def divisao(x, y):
    return x / y
menu = True
while menu:
	print("\n")
	print('Selecione um numero da operação desejada')
	print('1 - Soma')
	print('2 - Subtração')
	print('3 - Multiplicação')
	print('4 - Divisão')

	operacao = int(input("Escolha a operação desejada: "))

	num1 = int(input('Digite um numero:'))
	num2 = int(input('Digite mais um numero:'))

	if operacao == 1:
	    print('A soma é: ',add(num1, num2))

	elif operacao == 2:
	    print(subtracao(num1, num2))

	elif operacao == 3:
	    print(multiplicacao(num1, num2))

	elif operacao == 4:
	    print(divisao(num1, num2))

	elif operacao == 0:
		menu = False

	else:
	    print("\nOpção Inválida!")
	    
print('Fim')
