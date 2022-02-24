# python
# program 8. Demonstrate the use of lists.
#a. creat a list(using []/list())
l=[]
print(type(1),1)
a=list()
print(type(a).a)

# #b) Display contents of the list (using name of the list) 
l=[17,19.90, 12, "December", True] 
print ("contents of list are: ",1) 
print ()

# #c) Display the length of the list (using len()) 
print ("Length of list is: ",len (1)) 
print ()

# #d) Display the element in given position in the list (use subscripts []) 
print (l) 
print ("The First element in the list is: ",l[0]) 
print ()

# #  e. ADD ELEMENT TO THE LIST (USING ,APPEND(),insert(),extance()or concatnation)
# print("Add element to the list"("using append(),insert(),extance() or concatnation"))
# locals=[]
a=int(input(" Enter an element to be add "))
l.appent(a)
print(l)
l.append("GITAM")
l.append[17:12]

# #f) Remove elements from the list (using remove (object), pop ([index]) or del list[index] keyword) 
# print("Remove elements from the list (using remove (object),pop ([index]) or del list[index] keyword) ") 
print (l)
l.remove ("BLR")
print ("After deleting 'BLR from list: ",l)
l.pop() #by default it removes last element of the bise
print ("After deleting last element from, the list is,l")

# #g) Slice (take part from the list using index values and step value) list_name[start : stop : step]
print("The list is: ", l)
print (l [:3]) # printing first values from the list. 
print ()

# #h) sort() sorted () methods are used to sort the elements of the list 1- [6,3,2,5,9,12,4]
print (l)
sl=sorted (l)
print("The new sorted list is: ", sl)
print("The original list is remains unsorted", l)
l.sort () 
print("The original list is now sorted ",l)
print ()

# # i) reverse list (using [::-1] or reverse() method)
print ("The original list is: ",l)
l.reverse()
print("Now list is reversed ",l) 
print ("Using slicing ",l[::-1])
