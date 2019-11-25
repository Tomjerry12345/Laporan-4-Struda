#include <iostream>
#include <windows.h>
#include <conio.h>

using namespace std;

int counter = -1 , nilai[13] , pil;
char nama[13][13] , nim[13][13] , keterangan[13];

main()
{
  do {
  	
  	system("cls");
  	
  	cout << "counter : " << counter << endl;
		
	cout << "1.Input Data \n"
		 <<	"2.Cari \n"
		 <<	"3.Tampil \n"
		 << "Input Pilihan : ";
	cin >> pil;
	cout << endl;
	
	switch(pil)
	{
		
		case 1 :
			counter++;
			
			cout << "Input NIM : ";
			cin >> nim[counter];
			cout << "Input Nama : ";
			cin >>nama[counter];
			cout << "Nilai Akhir : ";
			cin >> nilai[counter];
			
			if ((nilai[counter] >= 80) && (nilai[counter] <=100))
			{
				keterangan[counter] = 'A';				
			}
			else if ((nilai[counter] >= 70) && (nilai[counter] <=79))
			{
				keterangan[counter] = 'B';				
			}
			else if ((nilai[counter] >= 60) && (nilai[counter] <=69))
			{
				keterangan[counter] = 'C';				
			}
			else if ((nilai[counter] >= 50) && (nilai[counter] <=59))
			{
				keterangan[counter] = 'D';				
			}
			else {
				keterangan[counter] = 'E';
			}
			break;
		
		case 3 :
			
			for (int a =counter; a >= 0;a--)
			{
				cout << "Data : " << a << endl;
				cout << "NIM : " << nim[a] << endl;
				cout << "Nama : " << nama[a] << endl;
				cout << "Nilai Akhir : " << nilai[a] << endl;
				cout << "Keterangan : " << keterangan[a] << endl;
				cout << endl << endl;
				getch();
			}	
			break;			
		}
	 } while(pil != 4);
}
