# DAY4-python
items = ("sai","kiran","nani",2,3,1.8)
print(items)
('sai', 'kiran', 'nani', 2, 3, 1.8)
type(items)
​
tuple
names = ("ganesh","mani","yashwanth","bunny")
sorted(names)
['bunny', 'ganesh', 'mani', 'yashwanth']
sorted(names,reverse = True)
['yashwanth', 'mani', 'ganesh', 'bunny']
snacks = ("pizza","burgur","cooldrink")
n = 3
repeated_tuple = snacks*n
print(repeated_tuple)
('pizza', 'burgur', 'cooldrink', 'pizza', 'burgur', 'cooldrink', 'pizza', 'burgur', 'cooldrink')
dish = ("chappathi","paneer")
food = snacks + dish
print(food)
('pizza', 'burgur', 'cooldrink', 'chappathi', 'paneer')
print("burgur" in snacks)
print("chicken" not in food)
True
True
for every_item in food:
    print(every_item)
pizza
burgur
cooldrink
chappathi
paneer
len(food)
5
marks = (90,40,69,54,78)
min(marks)
40
marks = (90,40,69,54,78)
max(marks)
90
numbers = (5,17,89,45,45.5,70,95)
print(numbers)
​
(5, 17, 89, 45, 45.5, 70, 95)
numbers[1:3]
(17, 89)
numbers[-1:1]
()
print(food)
food[3:6]
('pizza', 'burgur', 'cooldrink', 'chappathi', 'paneer')
('chappathi', 'paneer')
food[1:5]
('burgur', 'cooldrink', 'chappathi', 'paneer')
food[3:-2]
()
food[-2:3]
()
books = {"com_networks":5,"dbms":3,"com_graphis":5}
print(books)
type(books)
{'com_networks': 5, 'dbms': 3, 'com_graphis': 5}
dict
del books["dbms"]
print(books)
{'com_networks': 5, 'com_graphis': 5}
line = "i am sathyabama student"
word_count = {}
for word in line.split():
    if word not in word_count:
        word_count[word] = 1
    else:
        word_count[word] += 1
        
print(word_count)
{'i': 1, 'am': 1, 'sathyabama': 1, 'student': 1}
clear(books)

shop_items = {"snacks":5,"cloths":3,"foodreceipies":2}
len(shop_items)
3
str(shop_items)
"{'snacks': 5, 'cloths': 3, 'foodreceipies': 2}"
type(shop_items)
dict
shop_items.clear()
shop_items = {"snacks":5,"cloths":3,"foodreceipies":2}
shoped_items = shop_items.copy()
shoped_items
{'snacks': 5, 'cloths': 3, 'foodreceipies': 2}
shop_items = {"snacks":5,"cloths":3,"foodreceipies":2}
shop_items.keys()
dict_keys(['snacks', 'cloths', 'foodreceipies'])
shop_items.values()
dict_values([5, 3, 2])
shop_items.items()
dict_items([('snacks', 5), ('cloths', 3), ('foodreceipies', 2)])
print("no of clothes buyed:",shop_items.get("cloths"))
no of clothes buyed: 3
print("no of products delevred:",shop_items.get("products"))
no of products delevred: None
tuple = ('kadapa','vizag','tirupati','kurnool')
dict1 = dict.fromkeys(tuple)
print("dictionary :",dict1)
dictionary : {'kadapa': None, 'vizag': None, 'tirupati': None, 'kurnool': None}
dict2 = dict.fromkeys(tuple,"andhra_pradesh")
print("new values :",dict2)
new values : {'kadapa': 'andhra_pradesh', 'vizag': 'andhra_pradesh', 'tirupati': 'andhra_pradesh', 'kurnool': 'andhra_pradesh'}
shop_items = {"snacks":5,"cloths":3,"foodreceipies":2}
shop_items["snacks"] = 7
print(shop_items)
{'snacks': 7, 'cloths': 3, 'foodreceipies': 2}
