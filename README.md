- from random import random
pos = 0
largo = 18
def paso():
    return -1 if random() <0.5 else 1

for t int range (largo):
    pos = pos + paso()
    print (pos)
