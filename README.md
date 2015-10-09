# -WSQ08-Functions
#include iostream
#include math.h
using namespace std;

double addition  (double a, double b){
return a+b;
}


double sustraction (double a, double b){
return a-b;
}


double product (double a, double b){
return a*b;
}


double division (double a, double b){
return a/b;
}


int remainder (int a, int b){
return a%b;
}


int main(){


  double a;
  double b;
  cout<<"Wellcome to the new ultra super pro calculator where  "<<endl;
  cout<<"you can do subtraction, multiplication, division, reaminder and addition.  "<<endl;;


  cout<<"Please give a value"<<endl;
  
  cin>>a;
  
  cout<<"Please give a second value"<<endl;
  
  cin>>b;
  


cout<<"The addition of the numbers equals to "<< addition(a,b)<<endl;

cout<<"The sustraction of the numbers equals to "<< sustraction(a,b)<<endl;

cout<<"The product of the numbers equals to "<< product(a,b)<<endl;

cout<<"The division of the numbers equals to "<< division(a,b)<<endl;


cout<<"The remainder of the division equals to "<< remainder(a,b)<<endl;


return 0;
}
