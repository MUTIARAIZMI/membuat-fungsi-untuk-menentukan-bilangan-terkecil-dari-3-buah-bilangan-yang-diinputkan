# Membuat fungsi untuk menentukan bilangan terkecil dari 3 buah bilangan yang diinputkan


Coding program lengkap

    #include <iostream>
    using namespace std;

    int main()
    {
    int A,B,C;
    cout<<"Masukan angka 1 = ";
    cin>>A;
    cout<<"Masukan angka 2 = ";
    cin>>B;
    cout<<"Masukan angka 3 = ";
    cin>>C;

    if(A<B){
    if(A<C)
        cout<<"Angka terkecil adalah = "<<A;
        else
        cout<<"Angka terkecil adalah = "<<C;
    }
    else if(B<C)
    cout<<"Angka terkecil adalah = "<<B;
    else
    cout<<"Angka terkecil adalah = "<<C;
    return 0;

    }


Hasil program

![img](https://raw.githubusercontent.com/MUTIARAIZMI/membuat-fungsi-untuk-menentukan-bilangan-terkecil-dari-3-buah-bilangan-yang-diinputkan/master/bilangan%20terkecil.jpg)
