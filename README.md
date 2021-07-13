#include <iostream>
#include <string>

using namespace std;

int main(){
    
    double small_pizza_price, large_pizza_price;
    int total, s_number = 0, l_number = 0, points = 0;
    
    cout<<"How many small pizzas?" << endl;
    cin >> s_number; 
        
    cout<<"How many large pizzas?" << endl;
    cin >> l_number; 
        
    small_pizza_price = 8;
    large_pizza_price = 12;
    total = (l_number*large_pizza_price) + (s_number*small_pizza_price);
    points = total / 3;
        
    cout << " Your total bill for " << s_number << " small pizza(s) and " << l_number << " large pizza(s) is $" << total << ". You have earned " << points <<  " points " << endl; 
 
    return 0;
}
