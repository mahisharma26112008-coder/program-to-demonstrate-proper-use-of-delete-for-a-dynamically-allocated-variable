# program-to-demonstrate-proper-use-of-delete-for-a-dynamically-allocated-variable

#include<iostream>
using namespace std;

int main() {
    int *p = new int;

    cout << "Enter a number: ";
    cin >> *p;

    cout << "Value: " << *p << endl;

    delete p;
    p = nullptr;

    return 0;
}
