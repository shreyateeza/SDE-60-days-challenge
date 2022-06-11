## Things to revise
1. Row Column Zero
    i = 0 to R  
    j = 1 to C  
        if matrix[i][0] == 0   
            col= false  
        i, j = 0 => i=0 and j=0  
      
    i = R-1 to 0  
    j = C-1 to 1  
        if i=0 or j=0  
            i,j=0  
            if col = false => i=0  
  
2. Next Greater Permutation  
  
3. Inversion Count  
    N1 = mid-low+1  
    N2 = high-mid  
    inversionCount += (mid+1-low-i)  
