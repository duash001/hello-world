# hello-world
This is a start of something new


#include <iostream>
#include <iomanip>
#include <vector>
#include <algorithm>
#include <string>
#include <sstream>


using std::cin; using std::cout; using std::endl;


bool sortcol ( const std::vector<int> &a, const std::vector<int> & b ) {

    return ( a.size()     > b.size() );
}

int main () {


   std:: vector < std::vector <int>> myvec {{2,3},{5,6,7},{6,7,8}};
   
   for ( unsigned int i  = 0; i < myvec.size(); ++ i ) {
   
   for ( unsigned int j = 0; j < myvec.size(); ++j) {
    
      myvec[I][j];
   
   }
   
   }
   
for ( auto vec : myvec ) {

    for ( auto i : vec) {
    
      cout << i << " ";
    }
    
    cout << endl;
}

cout << " CREATING A NEW MATRIX " << endl;


sort ( myvec.begin(), myvec.end(), sortcol );

for ( auto vec : myvec ) {
   for ( auto i : vec) {
   
   
     cout << i << " ";
   }

}
   
   return 0;
   
   
  } 
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   


}
