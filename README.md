# Quiz01
Quiz01 submission for Jason Tellez

def matVec(matrix,vector):
    """
    This function takes a matrix and a vector, multiplies them together, and then returns the matrix-vector product. 
    """
    for i in range(len(matrix)):
      product = []
       # an empty list for the result (i.e. the result/product/b)
      entry = 0
       # a value that will be used to store each entry for the resulting matrix
      for j in range(len(vector)):
        entry += matrix[i][j] * vector[j]
         # indexes the new value for the entry
        product.append(entry)
         # adds value to the matrix
    return product
  

matrix1 = [[1,2,3],[4,5,6]]
matrix2 = [7,8,9]
matrix3 = "I'm a string"
vector1 = [7,8,9]
vector2 = [[1,2,3],[4,5,6]]
vector3 = 11
print(matVec(matrix1,vector1))
