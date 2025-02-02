# ds4all
phyton For Beginner
# The Aim
This session's goal is to familiarize you with programming concepts through the initial writing of structured instructions. After that, we'll quickly get started with Python using the  Jupyter Notebook environment. Python and programming will be introduced in this session. It is crucial to take the time to comprehend these fundamental ideas.

# Introduction to programming
their_name = input("What is your name?: ")
if their_name == "Jerry":
    print("I’m called that too")
else:
    print("I am awesome")
    their_name = input("What is your name?: ")
if their_name == "Jerry" or their_name == "Tom":
    print("I'm called that too")
else:
    print(" My name is unique")

    # even and odd numbers
    x=int(input("please enter the variable"))
if x % 2 == 0:
    print("the variable is even!")
else:
    print("the variable is odd")
    #Prime numbers
    x=int(input("Enter a no:"))
if x>1:
    for i in range(2,x//2):
        if(x%i)==0:
            print(x,"is not a prime number")
            break
    else:
        print(x,"is a prime number")

        #List using while loop
         A = [ 5, 2, 9, -1, 3, 12]
counter =0
while counter <len(A) :
    print(A[counter])
    if A[counter] == -1:
        break
    print(A[counter]**2)
    counter += 1
       #list using for loop
A = [ 5, 2, 9, -1, 3, 12]
for i in A:
    print(i)
    if i==-1:
        break
    print(i**2)


    A = [ 5, 2, 9, -1, 3, 12]
sum =0
for i in A:
    sum=sum+i
    print(sum)

mean=sum/len(A)
print(mean)

my_items = [ -5, 3, 72, 1, 9, 24, -3]

maximum_so_far = None
for elem in my_items:
    if maximum_so_far == None or elem > maximum_so_far:
        maximum_so_far = elem

print("Maximum Value: ", maximum_so_far)

A = [ 1, 6, 2, 7 ]
B = A[:]
B.remove( 6 )
print(A)
print(B)

B.append(10)
print(B)

results = []
bought_cost = [ 10.0, 12.55, 17.99 ] # Price you pay to the manufacturer for an item 
sale_price = [ 12.0, 11.50, 20.0 ] # Price you sell it for
profit=0
for i in range( len(bought_cost) ):
    results.append(sale_price[i] - bought_cost[i])
    profit=profit +results[i]
print(results)
print(profit)


#Dictionary and tuple
student_records = {
           "Ada": 98.0,
          "Bill": 45.0,
       "Charlie": 63.2
}
student_names= ["Neva","Kelley","Emerson"]
student_grades= [72.2,64.9,32.0 ]

for i in range(len(student_names)):
    student_records[student_names[i]] = student_grades[i]

print(student_records)

student_records = {
           "Ada": 98.0,
          "Bill": 45.0,
       "Charlie": 63.2
}
student_names= ["Neva","Kelley","Emerson"]
student_grades= [72.2,64.9,32.0 ]

for i in range(len(student_names)):
    student_records[student_names[i]] = student_grades[i]

print(student_records)

 for k, v in student_records.items():
    print(k,v)
