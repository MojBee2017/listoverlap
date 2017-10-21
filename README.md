# listoverlap
import random
a = set(random.sample(range(1,30), 12))#[random.sample(1,50),5) ]
print(a)
b = (random.sample(range(1,30), 12))
print(b)
clist=[elem for elem in a if elem in b]
print(clist) #returns the elements that are common to both lists

#alternatively,
flist=a.intersection(b)
print(flist)
