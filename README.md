# fraccionmixta.c++


//omegaup

#include <iostream>

using namespace std;

int main()
{
    int x, y, z;

    cout << "escribe un numero" << endl;
    cin >> x;

    cout << "escribe un numero" << endl;
    cin >> y;

    cout << "escribe un numero" << endl;
    cin >> z;

    if (x == y && x == z){
        cout << "el triangulo es  equilatero";
    }
    else if (x == y && x != z)&&(x == z && x != y){
         
    }
    else  {
    cout << "el triangulo es escaleno";
    } 
    if      
    //igualando a y

    if (y == x && y == z){
    cout << "el triangulo es  equilatero";
    }
    else if (y == z && x != x)&&(y == x && x != z){
    cout << "el triangulo es  isoseles";
    }
     
     else {
    cout << "el triangulo es escaleno";
    }
    //igualando a z

    if (z==x&&z==y){
                cout<<"el triangulo es  equilatero";
            }
            else if (z==x&&z!=y)&&(z==x&&z!=y){
                cout<<"el triangulo es  isoseles";
            }
             
            else{
                cout<<"el triangulo es escaleno";
            }

    return 0;
    }

