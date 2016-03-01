# Object-Oriented-Programming

Date : 2011/6/7

Purpose : Develope a BankAccount class for Parkville Bank, which contains fields and functions that a BankAccount needs. Create a class containing private fields that hold the account number, account balance, and interest rate. Create public member functions for the class.

Step:

   class BankAccount{
   
   public:
   BankAccount()
   {
   rate=0;
   }
   
   BankAccount(int num,double bal=0.0)
   {
    AccNum=num;
    AccBal=bal;
   
   }

   BankAccount(int Num,double Bal=0.0,double r=0.0)
   {
    AccNum=Num;
    AccBal=Bal;
    rate=r;
   }

   void setAccount(int n,double b)
   {
    AccNum=n;
   AccBal=b;
    }

   void setAccount2(int n,double b,double r)
   {
    AccNum=n;
    AccBal=b;
    rate=r; 
    }
