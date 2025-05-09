
#include <iostream>
using namespace std;

int main() {
    int a, b, c;

     Input three numbers
    cout << "Enter three numbers: ";
    cin >> a >> b >> c;

    // Find maximum
    int max;

    if (a >= b && a >= c)
        max = a;
    else if (b >= a && b >= c)
        max = b;
    else
        max = c;

    // Output result
    cout << "The maximum number is: " << max << endl;

    return 0;
}
