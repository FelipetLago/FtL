# FtL
#Fatorial em Python

def main():
    n = int(input("Digite um numero inteiro e positivo, que sera realizado o fatorial do mesmo: "))
    print("O fatorial do numero digitado eh", fatorial(n))

def fatorial(x):
    f = 1
    for num in range(1, x+1):          #o x+1, caso o x seria igual a 5, x+1=6, o 6 nao entra
        f *= num       #eh igual a f = f * num
    return f
main()
