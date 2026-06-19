#include <iostream>
#include <iomanip>   // for decimal formatting
using namespace std;

int main()
{
    // Step 1: Hard-coded identity
    string name = "Mansoor Ahmed Qureshi"; // My Name
    long long studentID = 250205395;   // Student ID

    cout << "Name: " << name << endl;
    cout << "Student ID: BS" << studentID << endl;

    // Step 2: Extract digits
    int d1 = (studentID / 100000000) % 10;
    int d3 = (studentID / 1000000) % 10;
    int d5 = (studentID / 10000) % 10;
    int d7 = (studentID / 100) % 10;
    int d9 = studentID % 10;

    cout << "\nExtracted Digits: ";
    cout << d1 << " " << d3 << " " << d5 << " " << d7 << " " << d9 << endl;

    // Step 3 & 4: Attendance Percentage (formula use kiya)
    float math = (d1 / 10.0) * 100;
    float physics = (d3 / 10.0) * 100;
    float english = (d5 / 10.0) * 100;
    float programming = (d7 / 10.0) * 100;
    float islamic = (d9 / 10.0) * 100;

    // Counters
    int cleared = 0, warning = 0, detained = 0;

    cout << fixed << setprecision(2);   // 2 decimal places

    cout << "\nCourse Report:\n";

    // Mathematics
    cout << "Mathematics: " << d1 << " classes, " << math << "% - ";
    if (math >= 75) { cout << "CLEARED"; cleared++; }
    else if (math >= 50) { cout << "WARNING"; warning++; }
    else { cout << "DETAINED"; detained++; }
    cout << endl;

    // Physics
    cout << "Physics: " << d3 << " classes, " << physics << "% - ";
    if (physics >= 75) { cout << "CLEARED"; cleared++; }
    else if (physics >= 50) { cout << "WARNING"; warning++; }
    else { cout << "DETAINED"; detained++; }
    cout << endl;

    // English
    cout << "English: " << d5 << " classes, " << english << "% - ";
    if (english >= 75) { cout << "CLEARED"; cleared++; }
    else if (english >= 50) { cout << "WARNING"; warning++; }
    else { cout << "DETAINED"; detained++; }
    cout << endl;

    // Programming
    cout << "Programming: " << d7 << " classes, " << programming << "% - ";
    if (programming >= 75) { cout << "CLEARED"; cleared++; }
    else if (programming >= 50) { cout << "WARNING"; warning++; }
    else { cout << "DETAINED"; detained++; }
    cout << endl;

    // Islamic Studies
    cout << "Islamic Studies: " << d9 << " classes, " << islamic << "% - ";
    if (islamic >= 75) { cout << "CLEARED"; cleared++; }
    else if (islamic >= 50) { cout << "WARNING"; warning++; }
    else { cout << "DETAINED"; detained++; }
    cout << endl;

    // Summary
    cout << "\nSummary:\n";
    cout << "CLEARED: " << cleared << endl;
    cout << "WARNING: " << warning << endl;
    cout << "DETAINED: " << detained << endl;

    return 0;
}
