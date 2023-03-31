#include <iostream>
using namespace std;

int main() {
    // Declaración de variables
    double radio, area;
    const double PI = 3.14159; // Declaración de constante pi

    // Pedimos al usuario el radio del círculo
    cout << "Ingresa el radio del círculo: ";
    cin >> radio;

    // Calculamos el área del círculo
    area = PI * (radio * radio);

    // Mostramos el resultado al usuario
    cout << "El área del círculo es: " << area << endl;

    return 0;
}
