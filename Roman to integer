//leetcode problem 13
//Roman numerals are represented by seven different symbols: I, V, X, L, C, D and M.

//Symbol       Value
//I             1
//V             5
//X             10
//L             50
//C             100
//D             500
//M             1000

//code part:
class Solution {
public:
int num(char c){
    if(c=='I'){
        return 1;
    }
    else if(c=='V'){
        return 5;
    }
    else if(c=='X'){
        return 10;
    }
    else if(c=='L'){
        return 50;
    }else if(c=='C'){
        return 100;
    }else if(c=='D'){
        return 500;
    }
    else if(c=='M'){
        return 1000;
    }return -1;
}
    int romanToInt(string s) {
        int index=0,sum=0;
        while(index<s.size()-1){
            if(num(s[index])<num(s[index+1])){
                sum-=num(s[index]);
                
            }else{
                sum+=num(s[index]);
                
            }index++;
        }
        sum+=num(s[index]);
        return sum;
        
    }
};
