n=int(input()
for i in range(1,n+1):
    if(i%3==0 and i%5==0):
         print("YummyMax")
    elif(i%3==0):
         print("Yummy")
    elif(i%5==0):
         print("Max")
    else:
         print(i)
