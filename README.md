# find-unique
def findunique(l):
    n=len(l)
    d={}
    for i in range(n):
        if a[i] in d:
            d[a[i]]+=1 
        else:
            d[a[i]]=1 
    print(d)
    for key,value in d .items():
        if value==1 :
            return key
a=[1,2,4,5,2,3,5,2,4,5,1,9,3]
print(findunique(a))
