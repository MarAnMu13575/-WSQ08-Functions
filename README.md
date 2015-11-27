# -WSQ08-Functions
#include <iostream>
#include <cmath>

using namespace std;

float Sum(float a, float b){
return (a+b);
}
float Rest (float a, float b){
return (a-b);
}
float Division(float a , float b){
return (a/b);
}
float Mult (float a , float b){
return (a*b);
}
int Reminder (int a, int b){
return (a%b);}

int main(){

float a;

float b;

int c;

cout <<"ingresa a"<<endl;
cin>> a;
cout <<"Ingresa b"<<endl;
cin>> b;
cout <<"Now choose an option"<<endl;

cout<<"Press 1 for sum"<<endl;

cout <<"Press 2 for rest"<<endl;

cout <<"Press 3 for div"<<endl;

cout <<"Press 4 for mult"<<endl;

cout <<"Press 5 for Rem "<<endl;

cin >>c;
if (c==1){
    cout <<Sum(a,b)<<endl;
}

if (c==2){
    cout <<Rest(a,b)<<endl;
}

if (c==3){

    cout <<Division (a,b)<<endl;
}

if (c==4){
    cout <<Mult (a,b)<<endl;
}

if (c==5){
    cout <<Reminder(a,b)<<endl;
}

return 0;
}

