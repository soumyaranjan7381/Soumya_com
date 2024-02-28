# Soumya_com
int num=145;
int sum=0;
int temp=num;
while(num>0)
{
   int rem=num%10;
   int fact=1;
   for(int i=1;i<=rem;i++)
   {
   fact=fact*i;
   }
   sum+=fact;
   num/=10;
   }
   if(sum==temp)
   {
   System.out.println("strong num");
   }else{
   System.out.println("not strong num");
   }
