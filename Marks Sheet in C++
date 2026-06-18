#include<iostream>
#include<string>
using namespace std;

int main()
{
    string subjectname[5];
    int obtainedmarks[5];
    int totalmarks[5];
    int overalltotalmarks=0;
    int totalobtainedmarks = 0;

    for(int i=0; i<5; i++)
    {
        cout << "Enter subject name: ";
        getline(cin, subjectname[i]);

        cout << "Enter total marks for " << subjectname[i] << ": ";
        cin >> totalmarks[i];

        cout << "Enter obtained marks for " << subjectname[i] << ": ";
        cin >> obtainedmarks[i];
        

		overalltotalmarks += totalmarks[i];
        totalobtainedmarks += obtainedmarks[i];
        cin.ignore(1000, '\n');
    }

    cout<<" Total Marks= " << overalltotalmarks<<endl;
    cout << "Total Obtained Marks = " << totalobtainedmarks<<endl;

    return 0;
}
