#include<iostream>

using namespace std;

int main()

{
    while(1)
{
            float bdt;

            float bp=(1/113.8);

            float ir=(1/1.14);

            float frnc=(1/92.37);

            float dutchmark=(1/47.72);

            float yen=(1/0.69);

            float dollar=(1/87.11);

            cout<<"Enter the Bangladeshi TAKA for Conversion :\n";

            cin>>bdt;

            cout<<"British Pounds :"<<bp*bdt<<endl;

            cout<<"Indian Rupee :"<<ir*bdt<<endl;

            cout<<"French franc :"<<frnc*bdt<<endl;

            cout<<"German Dutchmark :"<<dutchmark*bdt<<endl;

            cout<<"Japanese Yen :"<<yen*bdt<<endl;

            cout<<"USA dollar:"<<dollar*bdt<<endl;


            cout<<endl;
            cout<<endl;
            cout<<endl;
    }
    return 0;

}
