# Programa-que-suma-resta-divide-y-multiplique-
Trabajo de Iker-CDIA205
def sumar(a, b):
    return a + b

def restar(a, b):
    return a - b

def multiplicar(a, b):
    return a * b

def dividir(a, b):
    if b == 0:
        return "Error: No se puede dividir por cero"
    return a / b

def main():
    print("Calculadora básica")
    a = float(input("Ingresa el primer número: "))
    b = float(input("Ingresa el segundo número: "))

    print(f"Suma: {sumar(a, b)}")
    print(f"Resta: {restar(a, b)}")
    print(f"Multiplicación: {multiplicar(a, b)}")
    print(f"División: {dividir(a, b)}")

if __name__ == "__main__":
    main()
