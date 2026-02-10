
//Simple C++ program to check happy year using function and bool
#include <iostream>
using namespace std;
bool isHappy(int year){
   if(year%4==0){
      return true;
   }
   else{
      return false;
   }
}
//----------------------------------------
int main(){

int Year;
  cout<<"Enter the year:"<<endl;
  cin>>Year;

  if(isHappy(Year)){
   cout<<"Happy Year";
  }
  else{
   cout<<"Normal Year";
  }
     
   return 0;
}
