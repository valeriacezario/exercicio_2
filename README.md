Crescente: 

for i in range(20,0,-1):
if i != 13:
print(i)

2 opção: 

i = 20
while i > 0:
if i != 13:
print(i)
i -= 1

Decrescente: 

i = 20
for i in range(20,0,-1): 
i -= 1
if i ==13:
continue
print(i)
