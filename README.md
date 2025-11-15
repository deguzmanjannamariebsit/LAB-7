# LAB-7

#include <iostream>
using namespace std;

int main() {
    int grade, courseCode;

    cout << "Enter grade: ";
    cin >> grade;
    cout << "Enter course code (1-3): ";
    cin >> courseCode;

    if (grade >= 75)
        cout << "Result: Pass\n";
    else
        cout << "Result: Fail\n";

    switch (courseCode) {
        case 1:
            cout << "Course: Programming Fundamentals";
            break;
        case 2:
            cout << "Course: Data Structures";
            break;
        case 3:
            cout << "Course: Algorithms";
            break;
        default:
            cout << "Invalid course code.";
    }

    return 0;
}