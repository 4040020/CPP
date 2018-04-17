exercise1
---------------------
4維矩陣轉換
#include <iostream>
#include <iomanip>
using namespace std;
int fun(int array[4][4])
{
	int i,j,t;
	for(i=0;i<4;i++)
		for(j=0;j<i;j++)
		{
			t=array[i][j];
			array[i][j]=array[j][i];
			array[j][i]=t;
		}
		return 0;
}
int main()
{
	int i,j;
	int array[4][4]={{1,2,3,11},{4,5,6,12},{7,8,9,13}};
	cout << "Converted Front" <<endl;
	for(i=0;i<3;i++)
	{
		for(j=0;j<4;j++)
			cout << setw(7) << array[i][j] ;
		cout<< endl;
	}
	fun(array);
	cout << "Converted result" <<endl;
	for(i=0;i<4;i++)
	{
		for(j=0;j<3;j++)
			cout << setw(7) << array[i][j] ;
		cout<< endl;
	}
    return 0;
}


---------------------


exercise2
---------------------



---------------------

exercise3
---------------------



---------------------

exercise4
---------------------



---------------------

exercise5
---------------------



---------------------



