# learn data structure

## two sum:

\*\* Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

You can return the answer in any order. \*\*

### C++:

`include<iostream>

-using namespace std;`

- int main(){
- int x;
- int numbers[5] = {1,4,5,2,5};
- cout << "nhap x;"
- cin >> x;
- for(int i = 0; i< numbers.length; i++){
- for(int j = 1;j< numbers.length;j++){
- if(numbers[i] + numbers[j] = x){
- cout << "vi tri can tim la: "<< i << " va "<< j;
- }
- }
- }
- return 0;
- }`
