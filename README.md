# Refined_programs (FUNCTIONS)


# A function takes variable number of positional arguments as input.
# How to check if the arguments that are passed are more than 5.
def pos_arg_more( *args):
    if (len(args)) > 5:
        print("false")
    else:
        print("true")
pos_arg_more(1,6,7)

#Write a function to print the below output.
#  func("TRACXN", 0)  # Should print RCN
def word_(a,b):
    print(a[1::2])
word_("TRACXN", 1)
# func(""TRACXN"", 1)  # Should print TAX"
def word_(a,b):
    print(a[0::2])
word_("TRACXN", 1)

#to check the version of python
import sys
print(sys.version)

# Write a function to check if the number is Prime
def prime_num (num):
    if num ==1:
        print("not a prime")
    elif num>1 :
        for i in range(2,num):
            if num%i == 0:
                print("It is not a prime number")
                break
        else:
            print("It is a prime number")
    else:
        print("It is not a prime number")

prime_num(11)

# Write a method that returns the last digit of an integer. For example, the call of
# get_last_digit(3572) should return 2.
def get_last_digit(num):
    last_digit = num % 10
    print(f'The last digit of the num is',last_digit)
get_last_digit(3572)

# Make a function named tail that takes a sequence (like a list, string, or tuple)
# and a number n and returns the last n elements from the given sequence, as a list.
def tail(lst1,stng1,n1):
    tail1=[]
    tail1.append(lst1[-1])
    tail1.append(stng1[-1])
    num = n1%10
    tail1.append(num)
    return tail1
print(tail([1,2,3,4],'asc',245))


# Write function named is_perfect_square that accepts a number and
# returns True if it's a perfect square and False if it's not.
def is_perfect_square(num):
    if ((num)**(0.5)) * ((num)**(0.5)) == (num):
        print("It is a perfect sq")
    else:
        print("not a perfect sq")
is_perfect_square(63)


































