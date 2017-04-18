//******************************************************
// HEADER FILES USED IN THE PROJECT
//******************************************************

#include<fstream.h>
#include<ctype.h>
#include<iomanip.h>
#include<conio.h>
#include<stdio.h>

//******************************************************
// CLASS USED IN THE PROJECT
//******************************************************

class account
{
  int acno;
  char name[50];
  int deposit;
  char type;
Public:
  void create_account();    //function to get data from the user
  void show_account();      //function to show data on screen
  void modify();            //function to get new data from user
  void dep();               //function to accept amount and add to balance 
  void draw();              //function to accept amount and substract from balance
  void report();            //function to show data in tabular format
  int retacno();            //function to return account balance
  int retdeposit();         //function to return balance amount
  char rettype();           //function to return type of account
  };                        //class end here
