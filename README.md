# project3
# c++ program for calculating grades
#include<iostream>
using namespace std;
int main()
{
	int marks[6],i;
	float sum=0,avg;
	cout<<"enter marks in subject\n";
	for(i=0;i<6;i++)
	{
		cin>>marks[i];
		sum =sum+marks[i];
	}
	cout<< "your marks are:" <<sum;
	avg = sum/6;
	cout<<"\n your grade is :: ";
	
	if (avg>80)	
	{
		cout<<"[A]\n";
	}
	
	else if(avg>60 && avg<80)
	{
		cout<<"[B]\n";
	}
	
	else if(avg>40 && avg<60)
	{
		cout<<"[C]\n";
	}
	else
	{
		cout<<"[D]\n";
	}
	return 0;
}
