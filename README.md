my_list = []
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
my_list.insert(1, 15)
my_list.extend([50, 60, 70])
my_list.pop()  # Remove the last element
my_list.sort()
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)
print("my_list:", my_list)
Output:

yaml
Index of 30: 3
my_list: [10, 15, 20, 30, 50, 60]




