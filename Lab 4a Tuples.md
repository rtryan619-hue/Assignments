# Lab 4a Tuples

## This is my code for lab 4a

# Part 1a
x1 = input("Enter first value: ")
x2 = input("Enter second value: ")
x3 = input("Enter third value: ")
x4 = input("Enter fourth value: ")
x5 = input("Enter fifth value: ")

my_tuple = (x1, x2, x3, x4, x5)
print(my_tuple)
# part 1b. You can't assign one element in a tuple because tuples can't be changed.

# Part 1c

my_tuple = (1,2,3,4,3,2,1,2,3,5,4,3,2,1)
print("1:", my_tuple.count(1))
print("2:", my_tuple.count(2))
print("3:", my_tuple.count(3))
print("4:", my_tuple.count(4))
print("5:", my_tuple.count(5))

# Part 1d
my_tuple = (1,2,3,4,3,2,1,2,3,5,4,3,2,1)
print("Part c:", my_tuple)

my_tuple = my_tuple + my_tuple
print("Part d:", my_tuple)

# Part 1e. These are not legal because tuples can't be changed after you make them. x.append(1) does not work because tuples do not use append. x[1] = "hello" does not work because you can't change an item in a tuple. del x[2] does not work because you can't delete one item from a tuple.

# Part 2a

#The data type of one, two, three, and four is int.

one, two, three, four = (1, 2, 3, 4)
print(type(one))
print(type(two))
print(type(three))
print(type(four))
# Part 2b The * grabs the extra values and puts them into a list. So in the example a, b, *c = (1, 2, 3, 4), a gets 1, b gets 2, and c becomes [3, 4].

# Part 2c
x = (1, 2, 3, 4)
a, *b, c = x
print(a, b, c)

# Part 3
my_x = [100, 200, 300, 400]
my_y = (200, 300, 400, 500)

print("Index 0:", id(my_x[0]), id(my_y[0]))
print("Index 1:", id(my_x[1]), id(my_y[1]))
print("Index 2:", id(my_x[2]), id(my_y[2]))
print("Index 3:", id(my_x[3]), id(my_y[3]))

#I used id() to see the memory address of each value. Some of the addresses repeat because Python reused the same integer values in memory. Different numbers have different addresses.

# Challenges
# The main challenge I had with this was number 3. I kept thinking I was doing the code wrong because of the huge numbers it was printing out, but then I realized that was actually the point of the question.
