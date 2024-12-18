# josephus
josephus problem in python
def josephus(people):
    if people==1:
        return 1
    elif people%2==0:
        return 2*josephus(people/2)-1
    else:
        return int(2*josephus((1+people)/2)-3)%(people+1)

print(josephus417))
