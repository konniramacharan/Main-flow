#List creation                                                                              TASK 1 COMPLETED    by K Ramacharan (12079) 

lst = list() # or []
print(lst)

#Operations on List

#Appending Elements
lst.append(1)
lst.append(2)
lst.append(3)
lst.append(4)
print(f"Created List : {lst}")

#Removing Elements
lst.remove(2)
lst.pop()
print("Removing Elements")
print(lst)

#Modifying Elements
lst[0] = 4
lst[1] = 5
print("Modifying Elements")
print(lst)

#Accessing Elements
print(f"Fist element in the list : {lst[0]}")
print(f"Second element in the list : {lst[1]}")

#Length of List
print(f"Length of the list is : {len(lst)}")

#Clearnin List
print("Clearning the list")
lst.clear()





#Dictionary Creation
d = dict() # or {}
print(d)

#Operations on Dictionary

#Adding Elements
d['a'] = 1
d['b'] = 2
d['c'] = 3
d['d'] = 4
print(f"Created Dictionary : {d}")


#Removing Elements
del d['a']
d.pop('b')
print("Removing Elements")
print(d)

#Modifying Elements
d['c'] = 400
d['d'] = 555
print("Modifying Elements")
print(d)

#Accessing Elements
print(f"Value of 'c' in the dictionary : {d['c']}")
print(f"Value of 'd' in the dictionary : {d['d']}")
print(f"Value of 'e' in the dictionary : {d.get('e', 'Not Found')}")


#Length of Dictionary
print(f"Length of the dictionary is : {len(d)}")

#Clearnin Dictionary
print("Clearning the dictionary")
d.clear()
print(d)







#Set Creation
s = set() # or {}
print(s)

#Operations on Set

#Adding Elements
s.add(1)
s.add(2)
s.add(3)
s.add(4)
print(f"Created Set : {s}")

#Removing Elements
s.remove(2)
s.pop()
print("Removing Elements")
print(s)

#Modifying Elements
s.add(4)
s.add(5)
print("Modifying Elements") 
print(s)

#Accessing Elements
print(f"First element in the set : {list(s)[0]}")
print(f"Second element in the set : {list(s)[1]}")

#Length of Set
print(f"Length of the set is : {len(s)}")

#Clearnin Set
print("Clearning the set")
s.clear()
print(s)