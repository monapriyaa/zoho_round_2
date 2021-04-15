# zoho_round_2
a=input()
m=len(a)//2
a=a[m:]+" "+a[:m]
l=len(a)
t=" "
for i in range(1,l,2):
 for j in range(l-i,1,-2):
  print(" ",end='')
  print(" ",end='')
 print(a[:i])
