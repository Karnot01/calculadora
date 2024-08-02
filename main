from sumar import sumar
from resta import restar
from multiplicacion import multiplicar
from dividir import dividir
from suma_avanzada import suma_avanzada

def mostrar_menu():
    print("Calculadora")
    print("1. Sumar 2 números")
    print("2. Restar 2 números")
    print("3. Multiplicar 2 números")
    print("4. Dividir 2 números")
    print("5. Suma avanzada (N números)")
    print("6. Salir")

def main():
    while True:
        mostrar_menu()
        opcion = input("Seleccione una opción: ")

        if opcion == '1':
            num1 = float(input("Ingrese el primer número: "))
            num2 = float(input("Ingrese el segundo número: "))
            resultado = sumar(num1, num2)
            print(f"El resultado de la suma es: {resultado}")

        elif opcion == '2':
            num1 = float(input("Ingrese el primer número: "))
            num2 = float(input("Ingrese el segundo número: "))
            resultado = restar(num1, num2)
            print(f"El resultado de la resta es: {resultado}")

        elif opcion == '3':
            num1 = float(input("Ingrese el primer número: "))
            num2 = float(input("Ingrese el segundo número: "))
            resultado = multiplicar(num1, num2)
            print(f"El resultado de la multiplicación es: {resultado}")

        elif opcion == '4':
            num1 = float(input("Ingrese el primer número: "))
            num2 = float(input("Ingrese el segundo número: "))
            if num2 != 0:
                resultado = dividir(num1, num2)
                print(f"El resultado de la división es: {resultado}")
            else:
                print("Error: No se puede dividir por cero.")

        elif opcion == '5':
            numeros = input("Ingrese los números separados por espacios: ").split()
            numeros = [float(num) for num in numeros]
            resultado = suma_avanzada(numeros)
            print(f"El resultado de la suma avanzada es: {resultado}")

        elif opcion == '6':
            print("Saliendo...")
            break

        else:
            print("Opción no válida. Por favor, intente nuevamente.")

if __name__ == "__main__":
    main()
