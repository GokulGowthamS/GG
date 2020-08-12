predicting the random number by giving the max integer


#include<iostream>
#include<cstdlib>
#include<ctime>

using namespace std;

int main()
{
    int max,RN,sum=0;

    for(int i=sum;i<1;i++)
    {
        for(int j=i;j<1;j++)
        {
            for(int k=j;k<3;k++)
            {
             cout<<"Enter your max integer:";
             cin>>max;
             srand(time(0));
             RN=(rand()%max)+1;
             cout<<RN<<endl;
            }
        }
    }

}
