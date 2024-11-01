a = list(input().replace(" ", ""))
b = list(input().replace(" ", ""))

count =0
for i in a:
  if(b.__contains__(i)):
    b.remove(i)
    count +=1
n =((len(a) -count)+len(b))

flames =list("flames") 

while(len(flames) !=1):
  divisor =n %len(flames)
  if(divisor == 0):
    flames.pop()
  else:
    flames.pop(divisor -1)
    flames =flames[divisor-1:len(flames)]+flames[0:divisor-1]

if(flames[0] == "f"):
  print("Friendship")
elif(flames[0] == "l"):
  print("Love")
elif(flames[0] == "a"):
  print("Affection")
elif(flames[0] == "m"):
  print("Marriage")
elif(flames[0] == "e"):
  print("Enemy")
else:
 print("Sister")
