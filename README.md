# calculadora.py

def calculadora():
    print("--- Calculadora Python ---")
    print("Selecione a operação:")
    print("1 - Soma (+)")
    print("2 - Subtração (-)")
    print("3 - Multiplicação (*)")
    print("4 - Divisão (/)")

    escolha = input("Digite o número da operação (1/2/3/4): ")

    if escolha in ('1', '2', '3', '4'):
        try:
            num1 = float(input("Digite o primeiro número: "))
            num2 = float(input("Digite o segundo número: "))
        except ValueError:
            print("Erro: Entrada inválida. Digite números.")
            return

        if escolha == '1':
            print(f"Resultado: {num1} + {num2} = {num1 + num2}")
        elif escolha == '2':
            print(f"Resultado: {num1} - {num2} = {num1 - num2}")
        elif escolha == '3':
            print(f"Resultado: {num1} * {num2} = {num1 * num2}")
        elif escolha == '4':
            if num2 != 0:
                print(f"Resultado: {num1} / {num2} = {num1 / num2}")
            else:
                print("Erro: Divisão por zero não permitida.")
    else:
        print("Opção inválida.")

# Executar a calculadora
calculadora()
# Soma

eval("1+0")
eval("1+1")
eval("1+2")
eval("1+3")
eval("1+4")
eval("1+5")
eval("1+6")
eval("1+7")
eval("1+8")
eval("1+9")
