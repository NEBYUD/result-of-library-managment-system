# result-of-library-managment-system
#include <iostream>
#include <fstream>
using namespace std;
class books {
string title;
int quantity;
string type;
string author;
float price;
public:
    void setData(string t,string a,string ty,int q,float p){
    title=t;
    author=a;
    type=ty;
    quantity=q;
    price=p;
    }
    void getData(){
     cout << "Title: "<<title<<endl;
        cout << "Author: "<<author<<endl;
        cout << "Type: "<<type<<endl;
        cout << "Quantity: "<<quantity<<endl;
         cout << "Price: "<<price<<endl;
    }
};
