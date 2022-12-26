# 17.reverse-of-a-list
n = int(input())
l = list(map(int,input().split()))
l.sort(reverse=True)
print(l)
