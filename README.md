#include <iostream>
using namespace std;

int main ()
{
 int B, W, U,a;
 
 cout<< "Tugas Program"<<endl;
 cout<< "Program Menghitung"<<endl;
 cout<< "lama waktu menabung(dalam tahun)=";
 cin>>W;
 cout<< "uang yang ditabung = "; cin>>U;
 
 B = W * U;
 
 if (W<5)
 a=B * 0.1;
 
 else if (W>5||W==5)
 a=B * 0.15;
 
 
 cout<<"Besar Bunga Anda Adalah = "<<a;
 
 }
