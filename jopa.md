#include <iostream>
using namespace std;

int main()
{

double t, k, x, d;
cin >> t;
cin >> k;
cin >> x;
d = ((t+(3*k))/(t-3))+(((8*(t*t))-k)/5+8*(t+k));
cout << d;
return 0; 
  
}
