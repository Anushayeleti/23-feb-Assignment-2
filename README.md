n=int(input())
l=[]
for i in range(n):
    j=int(input())
    l.append(j)
for i in range(n-1,-1,-1):
    print(l[i])
    
    Output:enter number:5
           enter number:6
           enter number:7
           enter number:9
           enter number:2
           enter number:1
           1
           2
           9
           7
           6
           5
