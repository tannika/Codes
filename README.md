int isPalindrome(int A) {
  
    long long rev=0,num,n,d;
    if(A<0)
  return 0;
num=A;
  
  
  
    do
    {
        d = num%10;
        rev = rev*10 + d;
        num = num/10;
    }while(num!=0);
    
if (rev==A  )
return 1;

else 
return 0;
}
