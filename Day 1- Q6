def maxArea(A, Len) :
    area = 0
    for i in range(Len) :
        for j in range(i + 1, Len) :
           
            # Calculating the max area
            area = max(area, min(A[j], A[i]) * (j - i))
    return area
 
# Driver code
a = [ 1, 5, 4, 3 ]
 
len1 = len(a)
print(maxArea(a, len1))
