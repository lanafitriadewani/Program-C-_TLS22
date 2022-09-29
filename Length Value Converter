
#include <iostream>

using namespace std;
int main_menu();
double mile_menu();
double kilometre_menu();
double metre_menu();
double inch_menu();

int main()
{
    double Option;
    
    cout<<"Let's start converting length values!\n\n";
    cout<<"\t Select an option\n";
    cout<<"\t Type 1 to convert mile to kilometres\n";
    cout<<"\t Type 2 to convert kilometre to metres\n";
    cout<<"\t Type 3 to convert metre to centimetres\n";
    cout<<"\t Type 4 to convert inch to centimetres\n";
    cout<<"\t Type 0 to exit\n\n";
    cin>>Option;
    
    cout<<"============================================================\n\n";
    
    if (Option==1)
    {
        mile_menu();
    }
    
    else if (Option==2)
    {
        kilometre_menu();
    }
    
    else if (Option==3)
    {
        metre_menu();
    }
    
    else if (Option==4)
    {
        inch_menu();
    }
    
    else if (Option==0)
    {
        void exit(int);
    }
    
    else
    {
        cout<<"Sorry but the option you selected is not available\n";
        cout<<"Enter the option listed on the menu\n";
    }
    
    cout<<"\nThank you for using this converter!";
     
    return 0;
}

double mile_menu() //convert mile to kilometres
{
    double mile;
    double km;
    char YesNo;
    
    cout<<"Enter how many mile you would like to convert to kilometres\n";
    cin>> mile;
    km = mile*1.60934;
    cout<<"\n--> ";
    cout<<mile<< " mile is equal to "<<km<<" kilometres\n\n";
    
    cout<<"Would you like to continue task?\n";
    cout<<"Select Y for Yes or N for No to exit program\n";
    cin>> YesNo;
    
    if(YesNo=='Y')
    {
        cout<<"============================================================\n\n";
        main();
    }
    
    else if (YesNo=='N')
    {
        void exit(int);
    }
    
    return 0;
}

double kilometre_menu() //convert kilometre to metres
{
    double km2;
    double m;
    char YesNo;
    
    cout<<"Enter how many kilometre you would like to convert to metres\n";
    cin>> km2;
    m = km2*1000;
    cout<<"\n--> ";
    cout<<km2<< " kilometre is equal to "<<m<<" metres\n\n";
    
    cout<<"Would you like to continue task?\n";
    cout<<"Select Y for Yes or N for No to exit program\n";
    cin>> YesNo;
    
    if(YesNo=='Y')
    {
        cout<<"============================================================\n\n";
        main();
    }
    
    else if (YesNo=='N')
    {
        void exit(int);
    }
    
    return 0;
}

double metre_menu() //metre to centimetres
{
    double m2;
    double cm;
    char YesNo;
    
    cout<<"Enter how many metre you would like to convert to centimetres\n";
    cin>> m2;
    cm = m2*1000;
    cout<<"\n--> ";
    cout<<m2<< " metre is equal to "<<cm<<" centimetres\n\n";
    
    cout<<"Would you like to continue task?\n";
    cout<<"Select Y for Yes or N for No to exit program\n";
    cin>> YesNo;
    
    if(YesNo=='Y')
    {
        cout<<"============================================================\n\n";
        main();
    }
    
    else if (YesNo=='N')
    {
        void exit(int);
    }
    
    return 0;
}

double inch_menu() //inch to centimetres
{
    double inch;
    double cm2;
    char YesNo;
    
    cout<<"Enter how many inch you would like to convert to centimetres\n";
    cin>> inch;
    cm2 = inch*2.54;
    cout<<"\n--> ";
    cout<<inch<< " inch is equal to "<<cm2<<" centimetres\n\n";
    
    cout<<"Would you like to continue task?\n";
    cout<<"Select Y for Yes or N for No to exit program\n";
    cin>> YesNo;
    
    if(YesNo=='Y')
    {
        cout<<"============================================================\n\n";
        main();
    }
    
    else if (YesNo=='N')
    {
        void exit(int);
    }
   
    return 0;
}

