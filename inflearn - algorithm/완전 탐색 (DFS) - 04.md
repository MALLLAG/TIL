```py
import sys


def DFS(L, sum):
    if L==n:
        if sum==(total-sum):
            print('YES')
            sys.exit(0)
    else:
        DFS(L+1, sum+a[L])
        DFS(L+1, sum)


n=int(input())
a=list(map(int, input().split()))
total=sum(a)
DFS(0, 0)
print('NO')
``
