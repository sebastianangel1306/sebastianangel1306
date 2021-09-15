#include <iostream>

using namespace std;
//imprimir y contar los multiplos de 5 entre 1 y 500
int main()
{
 int i=0;
 int c=0;
 for (i=5; i <=500; i+=5){
    cout<<i<<endl;
    c= c+1;
 }
 cout <<"los multiplos de 5 entre 1 y 500 son : "<< c <<endl;

    return 0;
 }
