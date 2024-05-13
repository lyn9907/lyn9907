#include <iostream>

// Función que multiplica dos números enteros y devuelve el resultado
int multiplicar(int a, int b) {
    return a * b;
}

int main() {
    int num1 = 5;
    int num2 = 3;
    int resultado = multiplicar(num1, num2);

    std::cout << "La multiplicación de " << num1 << " y " << num2 << " es: " << resultado << std::endl;

    return 0;
}
