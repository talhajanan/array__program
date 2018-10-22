# array__program
#include<iostream>
using namespace std;

int main(){
int result1;
int result2=0;
int counter=0;
int temp=0;
int num[7]={10,11,12,13,14,15,16};
int sav[7];
//addition of arraytemp
//temp=num[0]+num[1]+num[2]+num[3]+num[4]+num[5]+num[7]

for(int j=0; j<=6;j++){
counter++;
temp=temp+num[j];
result1=temp/counter;

}
cout<<"average of values in array num is equal to = "<<result1<<endl;

// storing in array sav
for(int i=0;i<=6;i++){
result2=num[i]-result1;
sav[i]=result2*result2;
cout<<sav[i]<<endl;
}

return 0;
}
