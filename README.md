# calculator
def addNumbers(A,B): 
    for i in range (B): 
        C = A+1
        A = C
    return C


C = addNumbers(3,4) 
print(C)


def subtractNumbers(A,B): 
    for i in range (B): 
        C = A-1
        A = C
    return C


C = subtractNumbers(12,4) 
print(C)
          
      
      
      
      

def multiplyNumbers(A,B):
    C = A
    for i in range (B-1): 
        C = C + A
    return C


C = divideNumbers(3,4) 
print(C) 

 def divideNumbers(A,B): 
    for i in range(B+1):
    A=A-B
