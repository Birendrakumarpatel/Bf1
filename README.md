# Bf1
starting coding

#include <iostream>
using namespace std;
int main(){
int  a;
cout<<"enter half 180* rotate ";  
cin>>a; 
for(int i=1; i<=a; i++)
{ for( int j=1; j<=a; j ++){                            
    if(j<=i-1){
      cout<<" ";

    }else{
      cout<<"*";

    }
  }cout<<"\n";

}
int n;
cout<<" enter any number primr o";
int flag =0;

cin>> n;
 for(int a=2; a<n; a++){
  if(n%a==0){
    flag=1;
    cout<<"Not PRime\n"<<"  ";

      
 break;
   
  }


 } 
 if( flag==0){
  cout<<"\n Prime  ";
cout<<"   \n";

 }


 int m;cout<<" Enter  palindromic pattern";
  cin>>m;

 n=m;

 
for( int i=1; i<=n; i++){
  int j;
  
  for(j=1; j<=n-i; j++){

    cout<<" ";}
 
   int k=i;
   for(; j<=n; j++){
    cout<<k--<<" ";

   }
    k= 2;
    for(; j<=i+1;j++){
      cout<<k++<<" ";

    }
    cout<<"\n";
}


}



enter half 180* rotate 6
******
 *****
  ****
   ***
    **
     *
 enter any number primr o17

 Prime     
 Enter  palindromic pattern5
    1 
   2 1 
  3 2 1 
 4 3 2 1 
5 4 3 2 1 2 
