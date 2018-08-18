# Averaging-3-numbers-using-C-
Get an Average of 3 numbers C++


/****************************************************************

Arash Misaghi

Write a program that will read in 3 numebrs from users and
will print the average (to 2 decimal places) of those numebrs. 
****************************************************************/



#include<iomanip>
#include<iostream>
using namespace std;



int main() 
{



	float num1, num2, num3;	        // alocation of 3 numbers 
	float avg;			// average

	cout << "Please input the first number" << endl;	// getting 1st number from user 
	cin >> num1;
	cout << "Please input the second number" << endl;	
	cin >> num2;
	cout << "Please input the third number" << endl;		 
	cin >> num3;

	avg = float (num1 + num2 + num3) / 3;
	cout << "The average of the three numbers is " << setprecision(2)<< fixed << avg << endl; // 2 decimal
	

  	system("pause");
	return 0;

}
