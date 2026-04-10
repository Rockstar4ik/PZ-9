# PZ-9
<img width="766" height="273" alt="image" src="https://github.com/user-attachments/assets/c3169d59-ce19-4482-9cf1-6be3b98bdda0" />

#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    if (n == 1) {
        cout << "Один" << endl;
    } else if (n == 2) {
        cout << "Два" << endl;
    } else if (n == 3) {
        cout << "Три" << endl;
    } else {
        cout << "Ошибка" << endl;
    }

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    if (n == 1) {
        cout << "Понедельник" << endl;
    } else if (n == 2) {
        cout << "Вторник" << endl;
    } else if (n == 3) {
        cout << "Среда" << endl;
    } else if (n == 4) {
        cout << "Четверг" << endl;
    } else if (n == 5) {
        cout << "Пятница" << endl;
    } else if (n == 6) {
        cout << "Суббота" << endl;
    } else if (n == 7) {
        cout << "Воскресенье" << endl;
    } else {
        cout << "Неверный день" << endl;
    }

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    if (n == 12 || n == 1 || n == 2) {
        cout << "Зима" << endl;
    } else if (n >= 3 && n <= 5) {
        cout << "Весна" << endl;
    } else if (n >= 6 && n <= 8) {
        cout << "Лето" << endl;
    } else if (n >= 9 && n <= 11) {
        cout << "Осень" << endl;
    } else {
        cout << "Ошибка" << endl;
    }

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    char op;
    int a, b;
    cin >> op >> a >> b;

    if (op == '+') {
        cout << a + b << endl;
    } else if (op == '-') {
        cout << a - b << endl;
    } else if (op == '*') {
        cout << a * b << endl;
    } else if (op == '/') {
        if (b == 0) {
            cout << "Деление на ноль" << endl;
        } else {
            cout << a / b << endl;
        }
    } else {
        cout << "Ошибка" << endl;
    }

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    if (n == 5) {
        cout << "Отлично" << endl;
    } else if (n == 4) {
        cout << "Хорошо" << endl;
    } else if (n == 3) {
        cout << "Удовлетворительно" << endl;
    } else if (n == 1 || n == 2) {
        cout << "Плохо" << endl;
    } else {
        cout << "Ошибка" << endl;
    }

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    switch (n) {
        case 0:
            cout << "Ноль" << endl;
            break;
        case 1:
            cout << "Один" << endl;
            break;
        case 2:
            cout << "Два" << endl;
            break;
        case 3:
            cout << "Три" << endl;
            break;
        case 4:
            cout << "Четыре" << endl;
            break;
        case 5:
            cout << "Пять" << endl;
            break;
        case 6:
            cout << "Шесть" << endl;
            break;
        case 7:
            cout << "Семь" << endl;
            break;
        case 8:
            cout << "Восемь" << endl;
            break;
        case 9:
            cout << "Девять" << endl;
            break;
        default:
            cout << "Ошибка" << endl;
            break;
    }

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int a, b;
    int op;
    cin >> a >> b >> op;

    switch (op) {
        case 1:
            cout << a + b << endl;
            break;
        case 2:
            cout << a - b << endl;
            break;
        case 3:
            cout << a * b << endl;
            break;
        case 4:
            if (b == 0) {
                cout << "Деление на ноль" << endl;
            } else {
                cout << a / b << endl;
            }
            break;
        default:
            cout << "Ошибка" << endl;
            break;
    }

    return 0;
}
