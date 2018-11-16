# Praktikum5


#Latihan1

#Susunan algoritma untuk menginput bilangan 

 sebanyak-banyaknya sampai kondisi apabila yang 

 di iniput adalah angka 0.

 Kemudian tampilkan nilai paling besar dari bilangan 

 yang di inputkan.

#Berikut adalah kodenya

int main()
{

    int a,max=0;

    do{

    cout << "Masukan Bilangan : ";

    cin >> a;

    if (a>max)

        max=a;

    }

    while (a!=0);

    cout <<max;

    return 0;
}


#Berikut adalah hasilnya

 ![img](https://raw.githubusercontent.com/amirudin742/Praktikum5/master/Hasil1.png)

#Berikut adalah flowchartnya

![img](https://raw.githubusercontent.com/amirudin742/Praktikum5/master/Flowchart.png)


#Latihan2

#Menentukan Penjumlahan Bilangan Yang Benar dan Salah

#a.Alur Algoritmanya
	
	-Mendeklarasikan int a,b, dan c

	-Mendeklarasikan variabel a,b, dan c sebagai nilai input

	-Memasukan nilai inputan a,b,c

	-Membandingkan penjumlahan nilai a + b =c dan a+c=b dan c+b=a


c++
	
		if( (a+b==c) || (a+c==b) )

		{

    		cout<<"BENAR";

		}

		else if((b+c==a))

		{

    		cout<<"BENAR";

		}

		else

    	{

    	cout<< "SALAH";
    

#b.Berikut adalah kodenya

int main()

{
    int a,b,c;

    cout<<"Masukan nilai ke 1:";
    cin>>a;
    cout<<"Masukan nilai ke 2:";
    cin>>b;
    cout<<"Masukan nilai ke 3:";
    cin>>c;

    if( (a+b==c) || (a+c==b) )
    {
        cout<<"BENAR";
    }
    else if((b+c==a))
    {
        cout<<"BENAR";
    }
    else
        {
        cout<< "SALAH";
        }
}


#c.Berikut adalah flowchartnya

![img](https://raw.githubusercontent.com/amirudin742/Praktikum5/master/Flowchart2.png)


#d.Berikut adalah hasilnya

![img](https://raw.githubusercontent.com/amirudin742/Praktikum5/master/Hasil2/Hasil1.png)
![img](https://raw.githubusercontent.com/amirudin742/Praktikum5/master/Hasil2/Hasil2.png)
![img](https://raw.githubusercontent.com/amirudin742/Praktikum5/master/Hasil2/Hasil3.png)
![img](https://raw.githubusercontent.com/amirudin742/Praktikum5/master/Hasil2/Hasil4.png)
