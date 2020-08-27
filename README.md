# FizzBuzz-program
Take a user input n, in range of n if any value is divisible by both 3 and 5 then print FizzBuzz, If divisible by 3 only then print Fizz, if divisible by only 5 then print Buzz, otherwise if neither divisible by 3 nor by 5 then print the value .

n=int(input().strip())
fizzbuzz(n)
def fizzbuzz(n):
     for i in range(1,n+1):
            if i%3==0 and i%5==0:
                     print("FizzBuzz")
            elif i%3==0:
                 print("Fizz")
            elif i%5==0:
                 print("Buzz")
            else:
               print(i)
                 
              
