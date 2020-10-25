# Calculator-Git
System Integration Week 4 Analysis
#include<iostream>
#include<cmath>

using std:: cout;
using std:: cin;
using namespace std;

int aa,a,b;
void no();
int main(){

	
	
	cout<<"[1 Add]\n";
	cout<<"[2 Subtract]\n";
	cout<<"[3 Divide]\n";
	cout<<"[4 Multiply]\n";
	
	cout<<"Enter a Number: ";
	cin>>aa;
	
	switch(aa){

		case 1:{
		cout<<"Enter 1st number\n";
		cin>>a;
		cout<<"Enter 2nd number\n";
		cin>>b;
		
		aa=a+b;
		cout<<"Sum = "<<aa;
		
		cout<<"\n\n Try again?\n 1[yes] 2[no]\n";
		cin>>aa;
		system("cls");
		if (aa==1){
			
			main();
		}
		else if(aa==2){ 
	
		no();
	}
		break;
	}
	case 2: {

	
		cout<<"Enter 1stnumber\n";
		cin>>a;
		cout<<"Enter 2ndnumber\n";
		cin>>b;
		
		aa=a-b;
		cout<<"Subtract = "<<aa;
		
		cout<<"\n\n Try again? 1[yes] 2[no]\n";
		cin>>aa;
		system("cls");
		if (aa==1){
			
			main();
		}
		else if(aa==2){ 
	
		no();
	}
	break;
	}
	case 3: {

	
		cout<<"Enter 1st number\n";
		cin>>a;
		cout<<"Enter 2nd number\n";
		if (aa==1){
			
			main();
		}
		
		aa=a/b;
		cout<<"Divide = "<<aa;
		
		cout<<"\n\n Try again? 1[yes] 2[no]\n";
		cin>>aa;
		system("cls");
			
		if (aa==1){
			
			main();
		}
		else if(aa==2){ 
	
		no();
	}
	break;
	}
	case 4: {

	
		cout<<"Enter 1st number\n";
		cin>>a;
		cout<<"Enter 2nd number\n";
		cin>>b;
		
		aa=a*b;
		cout<<"Multiply = "<<aa;
		
		cout<<"\n\n Try again? 1[Yes] 2[no]\n";
		cin>>aa;
		system("cls");
	if (aa==1){
			
			main();
		}
	else if(aa==2){ 
	
		no();
	}
	break;
	}

}
}
void no()
{
	cout<<"Thank you!";
}
