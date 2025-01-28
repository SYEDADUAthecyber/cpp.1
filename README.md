# #include<iostream>
using namespace std;
int main()
{char news;
cout<<"Enter first letter of news channel name:";
cin>>news;
switch(news)
{case 'B':
	cout<<"*BBC news*";
	break;
 case 'G':
    cout<<"*Geo news*";
 	break;
 default:
 	cout<<"*There is no news channel like that to show you*";
}
return 0;
}
