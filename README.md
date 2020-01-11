# Patterns-level-2

# to understand codes in 'patterns level 2' lets first revise some basic concepts.
# Note:

* below, range(n) will provide starting 5 values when print(each) is called.
'''
n = 5

for each in range(n):   

    print(each)
'''

# Note:

* below, range(n, 0, -1) will do the same thing of printing 5 values but, it does so in reverse order.
* output: (5,4,3,2,1), if n =5.
* or you can say it will provide starting 5 values, in reverse order with a difference of 1.
* That is: 5-1 = 4, 4-1 = 3.....and so on.
'''
n = 5
for each in range(n, 0, -1):
    print(each)
'''
# Note:

* range(-n+1,n), first the loop will run '-n+1', which results in: -5+1 = -4, -4+1 = -3....till 0. 
* after this, loop will run 'n', which results in 0,1,2,3,4.
'''
n = 5
for each in range(-n+1, n):
    print(each)
'''
