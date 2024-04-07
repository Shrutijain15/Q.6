# Q.6
num=int(input("Enter a number : ")) isTrue=False if(num==1):   
print("1 is not a prime number") elif(num>1):   
  for i in range(2,num):  
     if(num%i==0):      
  isTrue=True      
  break 
  if(isTrue):   
  print(num,"is not a prime   
        number") 
  else:   
  print(num,"is a prime number")
