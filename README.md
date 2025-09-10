# -Group-Activity-4-Loops

#include <iostream>
using namespace std;

int main() {
    // FOR LOOP
    cout << "For Loop: ";
    for (int i = 1; i <= 9; i++) {
        cout << i << " ";
    }
    cout << endl;

    // WHILE LOOP
    cout << "While Loop: ";
    int countdown = 5;
    while (countdown > 0) {
        cout << countdown << " ";
        countdown--;
    }
    cout << "Happy Birth Day!! " << endl;

    // DO-WHILE LOOP
    int num;
    do {
        cout << "Enter a number greater than 0: ";
        cin >> num;
    } while (num <= 0);

    cout << "You entered: " << num << endl;

    return 0;
}
