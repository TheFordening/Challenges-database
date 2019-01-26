#include <iostream>
using namespace std;
int main()
    {
        double investmentamount;
        double annualinterest;
        int    numofyears;
        cout<<" Enter your investment amount"<< endl;
        cin >> investmentamount;
        cout<< " Enter your annual interest"<< endl;
        cin >> annualinterest;
        cout << "Enter the number of years" << endl;
        cin >> numofyears;
        annualinterest = annualinterest/100;
        double monthlyirate = annualinterest/12;
        double y = 1 + monthlyirate;
        double z = 1 + monthlyirate;
        for (int x=0; x < numofyears*12; x++)
        {
            y = y * z ;
        }
        double FIV = investmentamount* y ;
        cout << "Your FIV amount is..." << endl;
        cout << FIV;
        return 0;

    }
