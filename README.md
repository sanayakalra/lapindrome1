# lapindrome1
t=int(input())

for i in range(0,t):
    
	l1=[]
    l2=[]
    s=input()
    se=len(s)
    if se%2==0:
        for j in range (0,int(se/2)):
            l1.append(s[j])
        for k in range(int(se/2),se):
            l2.append(s[k])
    else:
        for j in range (0,int(se/2)+1):
            l1.append(s[j])
        for k in range(int(se/2),se):
            l2.append(s[k])
    A=sorted(l1)
    B=sorted(l2)
    if A==B:
        print("yes")
    else:
        print("no")
            
    l1=[]
    l2=[]
