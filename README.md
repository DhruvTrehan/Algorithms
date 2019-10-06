# Algorithms
Upload the basics algorithms codes so that beginner can get idea about algorithms easily
# What is algorithm ? 
/*An algorithm produces the same output information given the same input information, and several short algorithms can be combined to perform complex tasks such as writing a computer program. A cookbook recipe, a diagnosis, a problem solving routine, are some common examples of simple algorithms
*/

# Some Basic Algorithm

#1. ADD TWO NUMBERS 

STEP 1 : START 
STEP 2 : INPUT TWO NUMBERS AS A AND B 
STEP 3 : SET SUM = 0 
STEP 4 : SUM = A + B 
STEP 5 : PRINT SUM 
STEP 6 : END 

#2.Print wheather the no is even or odd ?

STEP 1 : START 
STEP 2 : INPUT ONE NUMBER AS N 
STEP 3 : CHECK THE CONDITION 
        IF (N % 2 == 0)
        {
            PRINT (IT IS EVEN)
        }
        ELSE 
        {
            PRINT (IT IS ODD)
        }
STEP 4 : END 

#3. Print multiplication table of a number 

STEP 1 : START 
STEP 2 : INPUT A NUMBER N 
STEP 3 : SET I = 1 
STEP 4 : IF ( I <= 1O)
STEP 5 : SUM = I * N ;
STEP 6 : PRINT SUM 
STEP 7 : INCREAMENT I BY 1 EACH TIME  
STEP 8 : STOP

#4. INPUT TO CHECK THE NUMBER IS PALLINDROME OR NOT 

STEP 1 : START 
STEP 2 : INPUT A NUMBER N
STEP 3 : SET SUM = 0 
STEP 4 : WHILE (N > 0 )
        N1 = N % 10 ;
        SUM = SUM * 10 + N1
        N = N / 10
STEP 5 : PRINT SUM
STEP 6 : STOP         

#5. Algorithm to Print Greatest of Three Numbers 

Step 1: Start
Step 2: Declare variables a,b and c.
Step 3: Read variables a,b and c.
Step 4: If a>b
           If a>c
              Display a is the largest number.
           Else
              Display c is the largest number.
        Else
           If b>c
              Display b is the largest number.
           Else
              Display c is the greatest number.  
Step 5: Stop

#6. Algorithm to print the roots of quadratic of equation 

Step 1: Start
Step 2: Declare variables a, b, c, D, x1, x2, rp and ip;
Step 3: Calculate discriminant
         D←b2-4ac
Step 4: If D≥0
              r1←(-b+√D)/2a
              r2←(-b-√D)/2a 
              Display r1 and r2 as roots.
        Else     
              Calculate real part and imaginary part
              rp←b/2a
              ip←√(-D)/2a
              Display rp+j(ip) and rp-j(ip) as roots
Step 5: Stop            

#7. Write a program to print the factorial of a number 

Step 1: Start
Step 2: Declare variables n,factorial and i.
Step 3: Initialize variables
          factorial←1
          i←1
Step 4: Read value of n
Step 5: Repeat the steps until i=n
     5.1: factorial←factorial*i
     5.2: i←i+1
Step 6: Display factorial
Step 7: Stop

#8. Write a program to print wheather the number is prime or not 

Step 1: Start
Step 2: Declare variables n,i,flag.
Step 3: Initialize variables
        flag←1
        i←2  
Step 4: Read n from user.
Step 5: Repeat the steps until i<(n/2)
     5.1 If remainder of n÷i equals 0
            flag←0
            Go to step 6
     5.2 i←i+1
Step 6: If flag=0
           Display n is not prime
        else
           Display n is prime
Step 7: Stop 

#9. Write a program to print fibonacci till n<=1000

Step 1: Start 
Step 2: Declare variables first_term,second_term and temp. 
Step 3: Initialize variables first_term←0 second_term←1 
Step 4: Display first_term and second_term 
Step 5: Repeat the steps until second_term≤1000 
     5.1: temp←second_term 
     5.2: second_term←second_term+first term 
     5.3: first_term←temp 
     5.4: Display second_term 
Step 6: Stop


