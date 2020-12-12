# fibonacci-numbers
x = int(input("enetr how many numbers u want: ")) #x = 100

n1=0
n2=1

y=0

if x<=0:
    print("pls enter positive integer!!");
elif x==0:
    print("fibonacci number is: ");
    print(n1);
elif x>0:
    print("fibonacci numbers are: ");
    while y<x:
        print(n1);

        nth = n1+n2

        n1 = n2
        n2 = nth

        y+=1

