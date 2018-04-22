# sumOfArray

#include "stdafx.h"			
#include<iostream>
#include<vector>
using namespace std;

int main()
{
	int num_of_elements = 0;
	cout<<"Enter the number of elements: "<<endl;
	cin>>num_of_elements;
	vector<int> array1(number_of_elements);	
	int sum_of_array;
	cout<<"Enter each element of the array and press Enter: "<<endl;
	for(int i = 0; i<num_of_elements; i++)
	{
		cin>>array1[i];
		sum_of_array += array[i];
	}
	cout<<"The sum of the array is: " <<sum_of_array;
	system("pause");
	return 0;
}
