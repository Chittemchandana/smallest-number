# smallest-number
# approach1
a = int(input("Enter the value for a :"))
b = int(input("Enter the value for b :"))
c = int(input("Enter the value for c :"))
#comparing integer ‘a’ with other two integer
if a<=b and a<=c:
	print("a is smallest")
#comparing integer ‘b’ with other two integer
elif b<=a and b<=c:
	print("b is smallest")
#comparing integer ‘c’ with other two integer
elif c<=a and c<=b:
	print("c is smallest")


# approach2
a = 14
b = 21
c = 67

smallest = 0

if a < b and a < c :
    smallest = a
if b < a and b < c :
    smallest = b
if c < a and c < b :
    smallest = c

print(smallest, "is the smallest of three numbers.")

# approach3 using elif
a = 33
b = 66
c = 22

smallest = 0

if a < b and a < c :
    smallest = a
elif b < c :
    smallest = b
else :
    smallest = c

print(smallest, "is the smallest of three numbers.")



# apprach4
# Finding smallest of three numbers

# Reading numbers
first = float(input('Enter first number: '))
second = float(input('Enter second number: '))
third = float(input('Enter third number: '))

# Making decision and displaying
if first >= second and first>=third:
    small = first
elif second >= first and second >= third:
    small = second
else:
    small = third

print('Smallest = %d' %(large))
