# ass-2-22-02-22
n=int(input())
k=1
for i in range(1,n+1):
    for j in range(1,i+1):
        print(j,end=' ')
    k+=1
    print('\n')
for i in range(n-1,0,-1):
    k+=1
    for j in range(1,i+1):
        print(j,end=' ')
    print('\n')
    
output:
1
1 2
1 2 3
1 2 3 4 
1 2 3 4 5
1 2 3 4 
1 2 3
1 2
1
