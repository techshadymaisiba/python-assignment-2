# python-assignment-2
my_list = []  # Create an empty list

my_list.append(10)  # Append elements 10, 20, 30, 40
my_list.append(20)
my_list.append(30)
my_list.append(40)

my_list.insert(1, 15)  # Insert 15 at the second position (index 1)

my_list.extend([50, 60, 70])  # Extend the list with [50, 60, 70]

my_list.pop()  # Remove the last element

my_list.sort()  # Sort the list in ascending order

index_30 = my_list.index(30)  # Find the index of value 30

print("Index of 30:", index_30)  # Print index of 30
print("Final list:", my_list)  # Print the final list
