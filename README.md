# Two-Rooks
# cook your dish here
t=int(input())
while t:
    a,b,c,d=map(int,input().split())
    if(a==c or b==d):
        print("Yes")
    else:
        print("No")
    t-=1
