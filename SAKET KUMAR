   #        **PROGRAMMING FOR PROGRAM SOLVING ESC-18105** 
   ##   NAME-*SAKET KUMAR*
   ##   ROLL NO-*1915066*
   ##   BRANCH-*CSE* 
   ##   SECTION-*CSE (B)*
      
      
      
  # **GURU NANAK DEV ENGENEERING COLLEGE,LUDHIANA** 
 
 # **1.PROGRAM TO ADD TWO NUMBER**
 ```
   #include<stdio.h>
     
    int main()
    {
       int a, b, c;
       
       printf("Enter two numbers to add\n");
       scanf("%d%d", &a, &b);
       
       c = a + b;
       
       printf("Sum of the numbers = %d\n", c);
       
       return 0;
    }

 ```
 
 # **2.PROGRAM TO PRINT TABLE USING FOR LOOP**
 ```  
 #include<stdio.h>
int main(){
	int i,n,c;
        scanf("%d",&n);
	for(i=1;i<=10;i++){
		if(i<5){
   
               c=n*i;
		printf(" %d * %d = %d    %d * %d = %d\n",n,i,c,n,10+i,n*(10+i));
		}
		else if(i>=5) 
		{c=n*i;
                  printf(" %d * %d = %d    %d * %d = %d\n",n,i,c,n,10+i,n*(10+i));
		}
	/*	else 

                    printf(" %d * %d = %d    %d * %d = %d\n",n,i,c,n,10+i,n*())
*/


  }
	return 0;
}
 ```
 
 # **3.PROGRAM TO CHECK ARMSTRONG NUMBER**
 ```
 #include<stdio.h>
int main(){
	int n,temp,rem,s=0;
	scanf("%d",&n);
	temp=n;
	while(temp!=0){
		rem=temp%10;
		s=s+rem*rem*rem;
		temp/=10;
	}
	if(s==n){
		printf("Armstrong number\n");
	}
	else
		printf("Not an Armstrong number\n");
	return 0;
}

 ```
 
 
 # **4. PROGRAM TO FIND THE AVERAGE OF N NUMBERS**
 ```
  #include <stdio.h>
    int main()
    {
        int n, i;
        float num[100], sum = 0.0, average;
        printf("Enter the numbers of elements: ");
        scanf("%d", &n);
        while (n > 100 || n <= 0)
        {
            printf("Error! number should in range of (1 to 100).\n");
            printf("Enter the number again: ");
            scanf("%d", &n);
        }
        for(i = 0; i < n; ++i)
        {
            printf("%d. Enter number: ", i+1);
            scanf("%f", &num[i]);
            sum += num[i];
        }
        average = sum / n;
        printf("Average = %.2f", average);
        return 0;
    }
 ```
 
 # **5. PROGRAM FOR BINARY SEARCH**
 ```
 #include<stdio.h>
int main()
{
 int c,first,last,middle,n,search,array[100];

printf("enter number of elements\n",n);
scanf("%d",&n);

printf("enter %d integers\n",n);

for (c=0;c<n;c++)
 scanf("%d",&array[c]);

  printf("enter value to find\n");
 scanf("%d", &search);

first=0;
last=n-1;
middle=(first+last)/2;

while(first<=last){
if (array[middle]<search)
first=middle+1;
else if (array[middle]==search){
printf("%d found at location %d.\n",search,middle+1);
break;
}
else 
last=middle-1;

middle=(first+last)/2;
}
if (first>last)
printf("not found! %d isn't present in the list.\n",search);

return 0;
}

 ```
 
 
 # **6. PROGRAM FOR BUBBLE SORT**
 ```
 
#include<stdio.h>
int main()
{
int a[20],i,n,k,temp;
printf("\n enter size of array:");
scanf("%d",&n);
printf("\n enter %d elements of array\n",n);
for (i=0;i<n;i++)
scanf("%d",&a[i]);
for (k=0;k<n-1;k++)
{
for (i=0;i<n-k-1;i++)
{
if (a[1]>a[i++])
{
temp =a[i];
a[i]=a[i+1];
a[i+1]=temp;
}
}
}
printf("\n array eliminate after sorting \n");
for (i=0;i<n;i++)
printf("%d",a[i]);
printf("\n");
return 0;
}
 ```
 
 # **7.PROGRAM FOR PRINT CALCULATOR**
 
 ```
 #include<stdio.h>

int main()
{
   int choice;
   long num1, num2, x;

   printf("Please choose your option:"
          "\n1 = Addition"
          "\n2 = Subtraction"
          "\n3 = Multiplication"
          "\n4 = Division"
          "\n5 = Squares"
          "\n6 = exit"
          "\n\nChoice: ");
   scanf("%d", &choice);

   //while loop check whether the choice is in the given range
   while(choice < 1 || choice > 6)
   {
      printf("\nPlease choose the above mentioned option."
             "\nChoice: ");
      scanf("%d", &choice);
   }

   switch (choice)
   {
   case 1:
      printf("Enter two numbers: \n");
      scanf("%ld %ld", &num1, &num2);
      x = num1 + num2;
      printf("Sum = %ld", x);
      break;

   case 2:
      printf("Enter two numbers: \n");
      scanf("%ld %ld", &num1, &num2);
      x = num1 - num2;
      printf("Subtraction = %ld", x);
      break;

   case 3:
      printf("Enter two numbers: \n");
      scanf("%ld %ld", &num1, &num2);
      x = num1 * num2;
      printf("Product = %ld", x);
      break;

   case 4:
      printf("Enter Dividend: ");
      scanf("%d", &num1);
      printf("Enter Divisor: ");
      scanf("%d", &num2);

     //while loop checks for divisor whether it is zero or not
     while(num2 == 0)
     {
        printf("\nDivisor cannot be zero."
               "\nEnter divisor once again: ");
        scanf("%d", &num2);
     }
     x = num1 / num2;
     printf("\nQuotient = %ld", x);
     break;

   case 5:
      printf("Enter any number: \n");
      scanf("%ld", &num1);
      x = num1 * num1;
      printf("Square = %ld", x);
      break;

   case 6:
   return;

   default: printf("\nError");
   }
}

 ```
 
 # **8. PROGRAM FOR WEEKDAYS**
 ```
 #include<stdio.h>
int main()
{
    int code;
printf("enter weekdays in number:");
scanf("%d",&code);
if(code==1)
printf("Monday");
else if(code==2)
printf("Tuesday");
else if(code==3)
printf("Wednesday");
else if(code==4)
printf("Thursday");
else if(code==5)
printf("Friday");
else if(code==6)
printf("Saturday");
else if(code==7)
printf("Sunday");
else
printf("invalid output");
return 0;
}

 ```
 
 
 # **9. PROGRAMING FOR FACTORIAL OF A NUMBER**
 ```
 #include<stdio.h>
struct fraction
{
int numerator;
int denominator;
};

int main()
{
struct fraction f1,f2,rf;
printf("enter numerator of the fraction1 : ");
scanf("%d",&f1.numerator);
printf("enter denominator of the fraction1 : ");
scanf("%d",&f1.denominator);

printf("enter numerator of the fraction2 : ");
scanf("%d",&f2.numerator);
printf("enter denominator of the fraction2 : ");
scanf("%d",&f2.denominator);

rf.numerator = f1.numerator*f2.numerator;
rf.denominator = f1.denominator*f2.denominator;
printf("resultant fraction : %d/%d\n",rf.numerator,rf.denominator);
return 0;
}

 
 ```
 
 
 # **10. PROGRAMING FOR FIZZ BUZZ**
 ```
 #include <stdio.h>
int main()
{
int a;
printf("enter any number : ");
scanf("%d",&a);
if (a%15 == 0)
{
printf("fizz_buzz");
}
else
if (a%3 == 0)
{
printf("fizz");
}
else 
if (a%5 == 0)
{
printf("buzz");
}
else 
{
printf("%d",a);
}
return(0);
} 

 
 ```
 
 
 # **11. PROGRAM FOR SUM OF FIRST 100 NUMBER**
 ```
 #include <stdio.h>
int main()
{
int i,sum = 0;
for(i = 0;i <= 100;i = i+1)
{
sum = sum + i;
}
printf("sum of 1 to 100 numbers is %d\n",sum);
return 0;
}

 ```
 
 
 # **12.PROGRAM FOR GCD OF A NUMBER**
 ``` 
 #include<stdio.h>
int main()
{
int m,n,r=1;
printf("\n enter value for m,n:");
scanf("%d,%d",&m,&n);
while(r!=0)
{
r=n%m;
n=m;
m=r;
}
printf("\n GCD=%d\n",n);
return 0;
}
   

 ```
 
 # **13.PROGRAM FOR GREATER OF 2 NUMBER**
 ```
 #include<stdio.h>
int main()
{
    int a,b;
printf("Enter any two no.");
scanf("%d%d",&a,&b);
if (a>b)
{
printf("a is greater");
}
else
{
printf("b is greater");
}
return 0;
}

 ```
 
 # **14. PROGRAM FOR GREATER OF 3 NUMBER**
 ```
 #include <stdio.h>

 

void main()

{

    int num1, num2, num3;

 

    printf("Enter the values of num1, num2 and num3\n");

    scanf("%d %d %d", &num1, &num2, &num3);

    printf("num1 = %d\tnum2 = %d\tnum3 = %d\n", num1, num2, num3);

    if (num1 > num2)

    {

        if (num1 > num3)

        {

            printf("num1 is the greatest among three \n");

        }

        else

        {

            printf("num3 is the greatest among three \n");

        }

    }

    else if (num2 > num3)

        printf("num2 is the greatest among three \n");

    else

        printf("num3 is the greatest among three \n");

}

 ```
 
 # **15.PROGRAM FOR LEAP YEAR**
 ```
 #include <stdio.h>
int main()
{
int i;
printf("enter any year : ");
scanf("%d",&i);
if (i%400 == 0)
{
printf("%d is leap year\n",i);
}
else 
printf("%d is not leap year\n",i);
return 0;
}

 ```
 
 
 # **16.PROGRAM FOR LINEAR SEARCH**
 ```
 #include<stdio.h>

int main()
{
 int array[100],search, c, n;
printf("enter number of elements in array\n");
scanf("%d", &n);

printf("enter %d integer(s)\n", n);

for (c=0;c<n;c++)
scanf("%d", &array[c]);

printf("enter a number to search\n");
scanf("%d", &search);

for (c=0;c<n;c++)
{
if (array[c]==search)
{ 
  printf("%d is presnt at location %d.\n",search, c+1);
  break;
  }
}
if (c==n)
 printf("%d isn't present in the array.\n",search);
 return 0;
}


 ```
 
 
 # **17. PROGRAM FOR MATRIX ADDITION**
 ```
 #include<stdio.h>
int main()
{
int a[10][10],b[10][10],c[10][10],n,m,i,j;
printf("enter the size of the matrix : ");
scanf("%d %d",&m,&n);

printf("enter the elements of matrix A : ");
for (i=0;i<n;i++)
{
for(j = 0;j<m;j++)
{
scanf("%d",&a[i][j]);
}
}

printf("enter the elements of matrix B : ");
for(i = 0;i<n;i++)
{
for(j=0;j<m;j++)
{
scanf("%d",&b[i][j]);
}
}

for(i = 0;i<n;i++)
{
for(j= 0;j<m;j++)
{
c[i][j] = a[i][j] + b[i][j];
printf("%d\n",c[i][j]);
}
}
return 0;
}

 ```
 
 
 # **18.PROGRAM FOR TRANSPOSE OF MATRIX**
 ```
 #include<stdio.h>
int main()
{
int a[10][10],b[10][10],n,m,i,j;
printf("enter the size of matrix A : ");
scanf("%d %d",&m,&n);
printf("enter the elements of matrix A row wise\n",m*n);
for(i = 0;i < m;i++)
{
for(j = 0;j<m;j++)
{
scanf("%d",&a[i][j]);
}
}
for(i = 0;i<m;i++)
{
for(j= 0;j<n;j++)
{
b[j][i] = a[i][j];
}
}
printf("\ntranspose is \n ");
for(i=0;i<n;i++)
{
for(j = 0;j<m;j++)
{
printf("%d\n",b[i][j]);
}
}
return 0;
}
 ```
 
 
 # **19. PROGRAM FOR  SUM OF DIGITS OF  A NUMBER**
 ```
   #include <stdio.h>
     
    int main()
    {
       int n, t, sum = 0, remainder;
     
       printf("Enter an integer\n");
       scanf("%d", &n);
     
       t = n;
     
       while (t != 0)
       {
          remainder = t % 10;
          sum       = sum + remainder;
          t         = t / 10;
       }
     
       printf("Sum of digits of %d = %d\n", n, sum);
     
       return 0;
    }

 ```
 
 
 # **20. PROGRAM FOR  PALINDROME NO.**
 ```
 #include<stdio.h>
int main()
{
int sum=0,digit;
int number,temp;
printf("\n enter any positive integer no.:");
scanf("%d",&number);
temp=number;
while(temp>0)
{
digit=temp %10;
temp/=10;
sum=sum*10+digit;
}
if (number==sum)
{
printf("\n%d is a pallindrome number\n",number);
}
else
printf("\n%d is not a pallindrome number\n",number);
return 0;
}

 ```
 
 
 # **21.SWAP 2 NUMBER USING CALL BY VALUE METHOD**
 ```
 #include <stdio.h>
 
 
void swap(int, int);
 
int main()
{
   int x, y;
 
   printf("Enter the value of x and y\n");
   scanf("%d%d",&x,&y);
 
   printf("Before Swapping\nx = %d\ny = %d\n", x, y);
 
   swap(x, y); 
 
   printf("After Swapping\nx = %d\ny = %d\n", x, y);
 
   return 0;
}
 
void swap(int a, int b)
{
   int temp;
 
   temp = b;
   b = a;
   a = temp;
    printf("Values of a and b is %d  %d\n",a,b);
}

 ```
 
 
 # **.22.SWAP 2 NUMBER USING CALL BY REFRENCE METHOD**
 ```
 #include <stdio.h>
 
void swap(int*, int*);
 
int main()
{
   int x, y;
 
   printf("Enter the value of x and y\n");
   scanf("%d%d",&x,&y);
 
   printf("Before Swapping\nx = %d\ny = %d\n", x, y);
 
   swap(&x, &y); 
 
   printf("After Swapping\nx = %d\ny = %d\n", x, y);
 
   return 0;
}
 
void swap(int *a, int *b)
{
   int temp;
 
   temp = *b;
   *b = *a;
   *a = temp;   
}

 ```
 
 
 
# **23. PROGRAM TO ENTER THE DETAILS OF EMPLOYEES USING STRUCTURE**
```
#include<stdio.h>
//#include<string.h>
struct employee
{
char name[20];
int age;
char department[20];
float salary;
};

int main()
{
struct employee aemployee;
printf("enter employee's name : ");
scanf("%s",&aemployee.name);
printf("enter employee's age : ");
scanf("%d",&aemployee.age);
printf("enter employee's department : ");
scanf("%s",&aemployee.department);
printf("enter employee's salary : ");
scanf("%f",&aemployee.salary);
printf("An employee %s of age %d of department %s has a salary of %f",aemployee.name,aemployee.age,aemployee.department,aemployee.salary);
return 0;
}

```


# **24.PROGRAM TO FIND THE PRODUCT OF FRACTIOONS USING STRUCTURES**
```
#include<stdio.h>
struct fraction
{
int numerator;
int denominator;
};

int main()
{
struct fraction f1,f2,rf;
printf("enter numerator of the fraction1 : ");
scanf("%d",&f1.numerator);
printf("enter denominator of the fraction1 : ");
scanf("%d",&f1.denominator);

printf("enter numerator of the fraction2 : ");
scanf("%d",&f2.numerator);
printf("enter denominator of the fraction2 : ");
scanf("%d",&f2.denominator);

rf.numerator = f1.numerator*f2.numerator;
rf.denominator = f1.denominator*f2.denominator;
printf("resultant fraction : %d/%d\n",rf.numerator,rf.denominator);
return 0;
}

```
