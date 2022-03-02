# subtraction-of-two-matrices
A=[ ] 

m=int(input("enter number of rows:")) 
n=int(input("enter numbr of columns:")) 

for i in range(m):           
   rows=[]            
   for j in range(n):                    
       k=int(input())                     
       rows.append(k)            
   A.append(rows) 

print(A)

B=[ ] 

m=int(input("enter number of rows:"))
n=int(input("enter numbr of columns:")) 

for i in range(m):            
     rows=[]           
     for j in range(n):                 
        k=int(input(" "))                  
        rows.append(k)          
     B.append(rows) 

print(B) 

result=[[0,0],[0,0]] 

for i in range(m):            
     for j in range(n):      
         
     result[i][j]=A[i][j]-B[i][j] 
print("resultant matrix:") 

for i in range(m):         
    for j in range(n):             
        print(result[i][j],end="   ")        
    print()
