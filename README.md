# ranju-kumari-lab-3

#include <iostream>

using namespace std;
class Math{
  public:
      int power(double m,int n = 2){
          double result = 1;
          for(int i=0;i<n;i++){
              result *=m; 
          }
          return result;
      }
};

int main()
{
    Math m1;
    cout<<"Called power function with single argument\n";
    cout<<m1.power(4);
    cout<<"\nCalled power function with two arguments\n";
    cout<<m1.power(4,5);
    
    return 0;
}
