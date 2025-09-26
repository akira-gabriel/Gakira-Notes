## Index.flatten
```
>>> a = np.array([[1,2], [3,4]])
>>> a.flatten()
array([1, 2, 3, 4])
>>> a.flatten('F')
array([1, 3, 2, 4])
```

Parameters :|**order** : {‘C’, ‘F’, ‘A’}, optional
Whether to flatten in C (row-major), Fortran (column-major) order, or preserve the C/Fortran ordering from a. The default is ‘C’.|
<br>
Returns : **y** : ndarray<br>
A copy of the input array, flattened to one dimension.|




## plt.subplots_adjust(hspace=0.4)
