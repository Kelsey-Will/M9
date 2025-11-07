#M9
#include <iostream>
using namespace std;

class Animal {
public:
    void speak() {
        cout << "Animal sound" << endl;
    }
};

class Dog : public Animal {
public:
    void speak() {
        cout << "Woof!" << endl;
    }
};

class Cat : public Animal {
public:
    void speak() {
        cout << "Meow!" << endl;
    }
};

int main() {
    Dog dog;
    Cat cat;

    dog.speak();
    cat.speak();

    doog.speak();
    cat.speak;

    return 0;
}
