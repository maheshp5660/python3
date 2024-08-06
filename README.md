# python3

## Make a Simple a Calculaor 


##Make a Simple Calulator 

print('''
+ ADD 
- Subtract 
* Multiple 
/ Divide 
    '''  )

num1 = eval(input("enter the value"))

num2 = eval(input("enter the Value"))



opr = input("enter the opeartor value (+,*,-,/)")

if opr=="+":
    print(num1 + num2 )
    
elif opr=="-":
    print(num1 - num2)
    
    
elif opr=="*":
    print(num1 * num2)
    
    
    
elif opr=="/":
    print(num1 / num2 )
    

    
    
else:
    print("suppose this sign are not be use so invalid")
    
    
