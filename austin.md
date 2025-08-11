#include <iostream>
using namespace std;

int main(){
	int Physics;
	int Chemistry;
	int Biology;
	int Mathematics;
	int Computer;
	
	cout<<"Input Physics Marks:";
	cin>>Physics;
	cout<<"Input Chemistry Marks:";
	cin>>Chemistry;
	cout<<"Input Biology Marks:";
	cin>>Biology;
	cout<<"Input Mathematics Marks:";
	cin>>Mathematics;
	cout<<"Input Computer Marks: ";
	cin>>Computer;
	int Average=(Physics+Chemistry+Biology+Mathematics+Computer)/5;
	cout<<"The Average Mark is "<<Average<<"\n";
	
	if(Average >= 90){
		cout<<"Grade A";
	}else if (Average >=80){
		cout<<"Grade B";
	}else if (Average >=70){
		cout<<"Grade C";
	}else if (Average >=60){
		cout<<"Grade D";
	}else if (Average >=40){
		cout<<"Grade E";
		
		
	}else if (Average <40){
		cout<<"Grade E";
	}
}
	
	
	
