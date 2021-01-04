# task-mayscoda
for interview purpose


If n<10
digSum(n)=n

else
digSum(n)=sum(digSum(n))



 
Program:      int digSum(int n)
              {
              int Sum=0;
              
              while(n>0||sum>9)
              {
              if(n==0)
              {n=sum;
              sum=0;
              }
              sum+=n%10;
              n/=10;
              return sum;
              }
              


soln= 
input=548399
output=2
explanation= the sum=5+4+8+3+9+9 = 38,
              digSum(x)=3+8=11
              hence 1+1=  2;
              
              
  soln=
  input=2477381
  output=5
  
  explanation= the sum of digits=2+4+7+7+3+8=23
  
                      digSum(x)=2+3=5;
                      
                      
              
              
       
              
