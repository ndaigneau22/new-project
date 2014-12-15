new-project
===========
list1 = [2, 5, 7, 11, 20, 50, 55, 60]

new_list = []
def only_even(x):
    for num in list1:
        if num % 2 == 0:
            new_list.append(num)
    return new_list

print only_even(list1)

def keep_even(list):
    return [num for num in list if num%2==0]
        

#return list in alphabetical order
list2 = ["Mom", "Dad", "Josh", "Andrew", "Steven"]
print list[3]
print list[1]
print list[2]
print list[0]
print list[4]

Extra Credit for SI 106
