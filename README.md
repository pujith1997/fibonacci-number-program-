# fibonacci-number-program-
program on Fibonacci number 
def fibonaci(n): # we are defining the function as fibonaci 
    
    a=0      # 0 is the first term by default for any number 
    b=1      # 1 is the first term by default for any number     
    
    if n == 1:
        print (a)
    else:
        print (a)
        print (b)
    
    for i in range(2,n):
        c = a+b
        a = b   # here the values shift from a to b ,and from b to c 
                    #this  is done to increase the order or to move forward else we will get only till 0,1,1
        b = c
        
        print(c)
        
        
fibonaci(12)        #enter the value ,number of fibonacci numbers
