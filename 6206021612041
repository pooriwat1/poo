#include <iostream>
#include <string>
using namespace std;
int main()
{
	char num;
	string user,userlogin,pass,passlogin;
	do
	{
		cout << "////////// MENU /////////\n1. Register\n2. Login\nQ. Exit Program\n-------------------------\n";
		cout << "Enter Menu : ";
		cin >> num;
		if (num=='1')
		{
			cout << "********** Register **********\nInput Username : ";
			cin >> user;
			cout << "Input Password : ";
			cin >> pass;
		}
		else if (num=='2')
		{
			cout << "********** Login **********\nInput Username : ";
			cin >> userlogin;
			cout << "Input Password : ";
			cin >> passlogin;
			if (user == userlogin && pass == passlogin )
			{
				cout << "Username or Password Correct ^___^\n";
			}
			else
			{
				cout << "!!!!Username or Password incorrect Please try again!!!!\n";
			}
		}
	}while (num!='Q');
		cout << "Exit Program" << endl;
	return(0);
}
