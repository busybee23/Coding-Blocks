## Problem Statment : 
Video : https://youtu.be/V0bbAlLAJ0A <br>

Help Manmohan to print pattern of a given number. See the output pattern for given input n = 5.

Sample Input<br>
```
5
```

Sample Output <br>
```
1
11
202
3003
40004
```
## SOLUTION : 
```
#include <bits/stdc++.h>
#include<iostream>
using namespace std;

int main() 
{
	int x;
	cin>>x;
	cout<<"1"<<endl;
	for(int i=1;i<x;i++){
		cout<<i;
		for(int j=1;j<i;j++){
			cout<<"0";
		}
		cout<<i;
		cout<<endl;
	}
	return 0;
}
```
