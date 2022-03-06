# HAFTA7




ÖDEV1 
#include <iostream>
using namespace std;
int main()
{

    int x,y;
    cout<<"1. Sayiyi Gir : ";
    cin >> x;
    cout<<"2. Sayiyi Gir : ";
    cin >> y;
    cout<<"Bolum : "<<x/y<<endl;
    cout<<"Kalan : "<<x%y;
    return 0;
}

  
  
  ÖDEV2
  
  
  
  
  
  
  
  
  ÖDEV3
  #include<iostream>

using namespace std;
int main()
{
  int sayi;
  int sayac=0;
  cout<<"BIR SAYI GIRINIZ:";

  cin>>sayi;

 for(int j=2; j<sayi; j++)
     {
      if(sayi % j == 0)
         {
          sayac++;
          break;
         }
     }
  if(sayac == 0)
     {
      cout<<"asaldir"<<endl;
     }
 else
      cout<<"asal degildir"<<endl;
 return (0);
}        
                                  
                                  
                                  
                                  
                                  
                                  

                                  
                                  
ÖDEV4
#include <iostream>
using namespace std;
int sayi=2;
void fonksiyon1()
{
     sayi = 5;
}
void fonksiyon2()
{
    int sayi = 7;
    }
int main()
{ fonksiyon1();
fonksiyon2();
cout << sayi;
}
                                  
