#!/bin/python

l = [4,5,7,9,10,12,11]
even_list = []
odd_list = []

for i in l:
   if (i % 2) == 0:
      even_list.append(i)
   else:
      odd_list.append(i)
print(even_list)
print(odd_list)
