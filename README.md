# second
N=int(input())
D=list()
for i in str(N):
    D.append(i)
for j in range(len(D)):
    if int(D[j])<9:
        D[j]="9"
        break
n=""#####
for u in D:
    n+=u
print(int(n))
