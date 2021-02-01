# assignment--1
#include <iostream>
#include <string>
using namespace std;

int main()
{    const int vat=12;


    cout << "WELCOME TO INF SUPERMARKET" << endl;


    string customer_Name;
    cout<<"Please enter customer name"<<endl;
    cin>>customer_Name;


   string items_Sold;
   cout<<"Here are the items being sold: 1. Printer 2. Phone 3.Table"<<endl;

    string attendant_Name;
   cout<<"Enter attendant name"<<endl;
   cin>>attendant_Name;


    int ID;
    cout<<"Please enter Unique ID"<<endl;
    cin>>ID;

    string item_Bought;
    cout<<"Enter item bought"<<endl;
    cin>>item_Bought;

    double printer=200;
    double phone=10;
    double table=50;
   double totalcost,totalamountpaid,balance;

   int quantity;
   cout<<"How many will you buy"<<endl;
   cin>>quantity;

     int moneynow;
    cout<<"how much do you have on you?"<<endl;
    cin>>moneynow;


    if( moneynow<printer || moneynow<phone || moneynow<table){
        cout<<"You are not eligible to purchase any item"<<endl;

    }
        else if(item_Bought=="printer" ){
            totalcost=(quantity*printer);

           cout<<"The total cost is: "<<totalcost<<endl;
            totalamountpaid=totalcost+vat;
            cout<<"Total amount to be paid with vat: "<< totalamountpaid<<endl;

            balance=moneynow-totalamountpaid;
            cout<<"Your balance after payment: "<<balance<<endl;


       cout<<"--------RECEIPT OF INF SUPERMARKET--------"<<endl;
       cout<<"               Customer name:            "<<customer_Name<<endl;
       cout<<"               Attendant name           "<<attendant_Name<<endl;
       cout<<"            Unique ID:                  "<<ID<<endl;
       cout<<"              Item bought:              "<<item_Bought<<endl;
       cout<<"            Quantity bought:            "<<quantity<<endl;
       cout<<"               Vat amount:              "<<vat<<endl;
       cout<<"               Total Cost:              "<<totalcost<<endl;
       cout<<"            Total amount paid:          "<<totalamountpaid<<endl;
       cout<<"                 Balance:               "<<balance<<endl;

       cout<<"Thank you for transacting with us our dearest customer,hope to see you again"<<endl;
}

       if( moneynow<printer || moneynow<phone || moneynow<table){
        cout<<"You are not eligible to purchase any item"<<endl;

    }
        else if(item_Bought=="phoneprice" ){
            totalcost=(quantity*phone);

           cout<<"The total cost is: "<<totalcost<<endl;
            totalamountpaid=totalcost+vat;
            cout<<"Total amount to be paid with vat: "<< totalamountpaid<<endl;

            balance=moneynow-totalamountpaid;

            cout<<"Your balance after payment: "<<balance<<endl;


       cout<<"--------RECEIPT OF INF SUPERMARKET--------"<<endl;
       cout<<"               Customer name:           "<<customer_Name<<endl;
       cout<<"           Attendant name:              "<<attendant_Name<<endl;
       cout<<"           Unique ID:                   "<<ID<<endl;
       cout<<"              Item bought:              "<<item_Bought<<endl;
       cout<<"            Quantity bought:            "<<quantity<<endl;
       cout<<"               Vat amount:              "<<vat<<endl;
       cout<<"               Total Cost:              "<<totalcost<<endl;
       cout<<"            Total amount paid:          "<<totalamountpaid<<endl;
       cout<<"                 Balance:               "<<balance<<endl;

       cout<<"Thank you for transacting with us our dearest customer, we to see you again"<<endl;

}
            if( moneynow<printer || moneynow<phone || moneynow<table){
        cout<<"You are not eligible to purchase any item"<<endl;

    }


        else if(item_Bought=="table" ){
            totalcost=(quantity*table);

           cout<<"The total cost is: "<<totalcost<<endl;
            totalamountpaid=totalcost+vat;
            cout<<"Total amount to be paid with vat: "<< totalamountpaid<<endl;

            balance=moneynow-totalamountpaid;

            cout<<"Your balance after payment: "<<balance<<endl;


       cout<<"--------RECEIPT OF INF SUPERMARKET--------"<<endl;
       cout<<"               Customer name:           "<<customer_Name<<endl;
       cout<<"           attendant name:               "<<attendant_Name<<endl;
       cout<<"           Unique ID:                  "<<ID<<endl;
       cout<<"              Item bought:              "<<item_Bought<<endl;
       cout<<"            Quantity bought:            "<<quantity<<endl;
       cout<<"               Vat amount:              "<<vat<<endl;
       cout<<"               Total Cost:              "<<totalcost<<endl;
       cout<<"            Total amount paid:          "<<totalamountpaid<<endl;
       cout<<"                 Balance:               "<<balance<<endl;

       cout<<"Thank you for transacting with us our dearest customer, we hope to see you again"<<endl;
}

    return 0;
}
