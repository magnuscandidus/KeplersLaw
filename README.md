# KeplersLaw
# cook your dish here
t=int(input())
while t:
    a,b,c,d=map(int,input().split())
    if(((a**2)/(c**3))==((b**2)/(d**3))):
        print("Yes")
    else:
        print("No")
    t-=1
