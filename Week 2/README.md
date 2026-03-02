# Data-Science-Machine-Learning-Lab
This is a weekly documentation of my Data Science and Machine Learning practical learning and skills. 

## Data Structures: Lists, Tuples, and Dictionaries
Storing data in different data structures involves different syntax and commands.
I used Google Colab to  create different data structures to manage a list of friends, as follows:

### Creating a list  in Python
- This creates store items and allows modifications

friends = ['John', 'Peter', 'Mary', 'Agnes', 'Paul']
print(friends)

![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/List.png) 

- The list of friends is further modified using the append, extend, insert, remove, pop, index, count, sort, and reverse functions. 
#### Append
- The append function is used to add items to an existing list

  #Adding more friends to my list using the Append operation

friends = ['John', 'Peter', 'Mary', 'Agnes', 'Paul']

more_friends = ['Blessing', 'James', 'Faith', 'Favour']

friends.append(more_friends)

print(friends)

![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/List_append.png)

#### Extend
- Extend is used to add items or list to the end of another list (without returning list)

   #using extend  to add more friends without returning list

friends = ['John', 'Peter', 'Mary', 'Agnes', 'Paul']

more_friends = ['Blessing', 'James', 'Faith', 'Favour']

friends.extend(more_friends)

print(friends)

![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/List_extend.png)

#### Insert
- Insert function is used to add an item to a list

  #using the insert operation to add a name to the friend list as the first friend.

friends = ['John', 'Peter', 'Mary', 'Agnes', 'Paul', 'Blessing', 'James', 'Faith', 'Favour']

friends.insert(0, 'Angela')

print(friends)

![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/List_insert.png)

#### Remove
- Remove is used to remove an item from a list.

  #using the remove function to remove a name that from friends

friends = ['Angela', 'John', 'Peter', 'Mary', 'Agnes', 'Paul', 'Blessing', 'James', 'Faith', 'Favour']

friends.remove('Paul')

print(friends)

![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/List_remove.png)

#### Pop
- Pop function is used to remove an item from list and see the item that is being removed

  #using the pop operation to remove a name and see the name removed from the list

friends.pop(2)   # 2 is the index for peter.

![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/List_pop.png)

#### Index
- Index is used to find the position of an item in the list

#using index operation to find the position of James in the list.

friends.index('James')

![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/List_index.png)

#### Count
- Count is used to count the number of times an item occurred in a list

#using the count operator to count the number of times a name was listed in friends.

friends.count('Blessing')

![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/List_count.png)

#### Sort
- Sort is used to arrange a list in ascending order

#using *sort function* to arrange the names in ascending order

friends.sort()

print(friends)

![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/List_sort.png)

#### Reverse 
- Reverse function is used to arrange names in a descending order

#using the reverse function to arrange the names in a descending order

friends.reverse()

friends
![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/List_reverse.png)

### Tuple
- Tuple creates immutable collection of items
- It can only be accessed with functions such as count, and index

#creating a tuple

myfriends = ('Agnes', 'Angela', 'Blessing', 'Faith', 'Favour', 'James', 'John', 'Mary', 'Faith')

print(myfriends)

![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/Tuple.png)

#### Count

#the count function in Tuple - to count the number of times an item occured

myfriends.count('Faith')

![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/Tuple_count.png)

#### index

#index in tuple

myfriends.index('Favour')
![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/Tuple_index.png)

### Dictionary
- Dictionary creates an ordered collection of key-value pairs.

  #Creating a Disctionary that contains the details of my friends.

myfriends_details = dict([('names',['Agnes', 'James', 'John', 'Mary',]),
                          ('Age', [20, 36, 27, 25]),
                           ('City', ['Lagos', 'Abuja', 'Enugu', 'Kaduna'])])

print(myfriends_details)

print(myfriends_details.get('names'))

print(myfriends_details.get('Age'))

print(myfriends_details.get('City'))

![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/Dictionary.png)

### Nested Dictionary
#using nested dictionary to organise the names

myfriends_details = {'friend1':{'name': 'Agnes', 'Age': 20, 'City': 'Lagos'},
                     'friend2': {'name': 'Mary','Age': 36, 'City': 'Kaduna'},
                     'freind3': {'name':'James', 'Age': 27, 'City': 'Abuja'},
                     'friend4': {'Name': 'John', 'Age': 25, 'City': 'Enugu' }
                     }


print(myfriends_details.get('friend1'))

print(myfriends_details.get('friend2'))

print(myfriends_details.get('freind3'))

print(myfriends_details.get('friend4'))

![](https://github.com/sopy-anne/Data-Science-Machine-Learning-Lab/blob/main/Nexted_Dictionary.png)

