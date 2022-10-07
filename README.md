# myreo2


def myfunc(lis,num):
    lis1=[]
    for i in lis:
        if i % 2 !=0:
           lis1.append(i)
    return lis1
print(myfunc([1,11,7,8,-1,6],11))
print(myfunc([6,8,2],11))