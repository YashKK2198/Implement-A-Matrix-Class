# Implement-A-Matrix-Class
In this project I have implemented a matrix class in Python. Specifically, I  have implemented the following methods


class Matrix:
  def determinant(self):
      # your code


  def trace(self):
      # your code


  def inverse(self):
      # your code


  def transpose(self):
     # your code


  # Overloaded operators

  def __add__(self,other):
    # your code


  def __sub__(self,other):
    # your code


  def __mul__(self,other):
    # your code
    
    
    
    
   When my class is working properly I will be able to manipulate matrices in code as if they were regular numbers (for the most part).
   For example:
    
    
    
    
    
 > A = Matrix([ 
  [2,4], 
  [3,1] 
])
> print( A.transpose())
  2.0  3.0
  4.0  1.0
>
> I = Matrix([ 
    [1,0], 
    [0,1] 
])
>
> print(A*I)
  2.0  4.0
  3.0  1.0
>
> print(A * A.inverse())
  1.0  0.0
  0.0  1.0
