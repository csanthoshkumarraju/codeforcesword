# codeforcesword
s = input()
l,u = 0,0
for i in s :
    if (i >= 'a' and i <= 'z'):
        l = l+1
    if ((i >= 'A' and i <= 'Z')):
        u = u + 1
if l >= u :
    print(s.lower())
else:
    print(s.upper())
