# display grade 
 #include<iostream>
using namespace std;
int main()
{
int tmarks;
char ch;
cout<<"enter your total marks"<<endl;
cin>>tmarks;
switch(tmarks)
{
case 90:
ch='A';
break;
case 80:
ch='B';
break;
case 70:
ch='C';
break;
case 60:
ch='D';
break;
default:
ch='f';
break;
}
cout<<"your grade is="<<ch<<endl;
return 0;
}
