set={22,55,12,'Hello','hey',22.41}
#membership operators
print(22 in set)
print('hey' in set)
print('hoy' in set)
print(len(set))
t={22,55,12}
print(t.issubset(set))
print(t<=set)
print(set.issuperset(t))
print(set>=t)
print(t==set)
#union
s1={1,2,3,4,5}
s2={4,5,6,7,8}  #union-->1,2,3,4,5,6,7,8
print(s1.union(s2))
print(s1|s2)  #--> s1 or s2
#intersection-->4,5
print(s1.intersection(s2))
print(s1&s2)  #-->s1 and s2
#symmetric differnce--> 1,2,3,6,7,8
print(s1.symmetric_difference(s2))
print(s1.difference(s2))
print(s1-s2)
print(s2.difference(s1))
print(s2-s1)
s1copy=s1.copy()
print(s1copy)
#add
s={1,2,3,4,5}
print(s)
s.add(77)
print(s)
#remove
s.remove(77)
print(s)
s.discard(77)
print(s)
#traversing
for i in s:
    print(i,end=' ')
