class Solution {
public boolean checkPerfectNumber(int num) {
if(num<=0) return false;
int s=0;
for(int i=1;i<=num/2;i++)
if(num%i==0) s=s+i;
return (s==num);
}
}
