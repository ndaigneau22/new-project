new-project
===========
#return each number in nums with the amount of times it appears in the list.
nums = [0,1,2,3,4,4,5,6,6,7,8,8,8]
d = {}
for x in nums:
    if x in d:
        d[x] = d[x] + 1
    else:
        d[x] = 1
print d

#return list in alphabetical order
list = ["Mom", "Dad", "Josh", "Andrew", "Steven"]
print list[3]
print list[1]
print list[2]
print list[0]
print list[4]

Extra Credit for SI 106
