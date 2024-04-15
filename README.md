# Aula-1-prog-1
X= 312
Xt = X
Bin= ""
while X != 0:
    if (X%2)==0:
        Bin="0"+Bin 
    else:
        Bin="1"+Bin
    X= X//2
    print(Bin)
print(str(Xt)+" = 0b"+Bin)
