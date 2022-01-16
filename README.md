# while_do-while_for

#include <iostream>

using namespace std;

int main()
{
    //while,do while,for
    int pil;

    cout<< "========menu========"<<endl;
    cout<< "1.while           \n"<<endl;
    cout<< "2.dowhile         \n"<<endl;
    cout<< "3.for             \n"<<endl;
    cout<< "===================="<<endl;
    cout<< "masukkan pilihan yang di inginkan [1/2/3] :";
    cin>>pil;
    switch (pil){
    case 1:
        //while
        int i=1;
         while(i <=25){
            cout<<i<<endl;
            i++;
         }

        break;
   case 2:

        //do while
        int a = 11;

	do {
			cout<<a<<endl;
		a++;

	} while(a <= 10);
	cout<<"Nilai terakhir a = "<<a<<endl;

	break;
    case 3:
           //for
            int a;
            cin>>a;
	for(a = 1; a<= 10;a++) {
		cout<<"a = "<<a<<endl;
    }

	break;

           }
    return 0;
}
