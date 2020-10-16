## Sorting Algorithms:

[Bubble Sort: Click here for demo](https://anisurrahmanlikhon.github.io/Bubble-Sort-Algorithm/)
```markdown

1. swapped = true
2. while swapped
3.   swapped = false
4.   for j from 0 to N - 1
5.	if a[j] > a[j + 1]
6.		swap( a[j], a[j + 1] )
7.		swapped = true
```

[Insertion Sort-1: Click here for demo](http://rosulek.github.io/vamonos/demos/insertion_sort.html)
```markdown

InsertionSort(A):

1. for j = 2 to A.length		
2. key = A[j]		
3. i = j - 1
4. while i > 0 and A[i] > key		
5. A[i + 1] = A[i]
6. i = i - 1		
7. A[i + 1] = key
```
[Insertion Sort-2: Click here for demo](https://insertion-sort-demo.herokuapp.com/index.html)
```markdown

1. const insertionSort = function (array) {
2.  for(let i = 1; i < array.length; i++) {
3.       const currentValue = array[i];
4.      let j;

5.      for(j = i - 1; j >= 0; j--) {
6.      if(array[j] <= currentValue) break;
7.       array[j + 1] = array[j]
8.      }

9.       array[j + 1] = currentValue;
10.    }
11. return array;
12.  }
```

[Selection Sort: Click here for demo](http://rosulek.github.io/vamonos/demos/selection_sort.html)
```markdown

SelectionSort(A):

1. for i = 0 to A.length-2  //find smallest item in A[i..]		
2. m = i		
3. for j = i+1 to A.length-1		
4. if A[j] < A[m]		
5. m = j		
6. swap A[i] and A[j]
```
[Merge Sort: Click here for demo](http://rosulek.github.io/vamonos/demos/mergesort.html)
```markdown

MergeSort(A,p,r):
		
1. if p < r		
2. q = [(p+r)/2]		
3. MergeSort(A,p,q)	
4. MergeSort(A,q+1,r)	
5. Merge(A,p,q,r)

Merge(A,p,q,r):	
	
1. n1 = q - p + 1		
2. n2 = r - q		
3. let L, R be new arrays		
4. for i = 1 to n1	
5. L[i] = A[p+i-1]		
6. for j = 1 to n2		
7. R[j] = A[q+j]		
8. L[n1+1] = ∞		
9. R[n2+1] = ∞		
10. i = 1		
11. j = 1		
12. for k = p to r		
13. if L[i] ≤ R[j]		
14. A[k] = L[i]		
15. i = i + 1		
16. else		
17. A[k] = R[j]		
18. j = j + 1
```

[QuickSort: Click here for demo](http://rosulek.github.io/vamonos/demos/quicksort.html)
```markdown

Quicksort(A,p,r):	
1. if p < r		
2. q = Partition(A,p,r)		
3. Quicksort(A,p,q - 1)		
4. Quicksort(A,q + 1,r)

Partition(A,p,r):		
1. i = p-1		
2. for j = p to r-1		
3. if A[j] ≤ A[r]		
4. i = i + 1		
5. exchange A[i] with A[j]		
6. exchange A[i+1] with A[r]		
7. return i+1
```
[Stooge Sort: Click here for demo](http://rosulek.github.io/vamonos/demos/stoogesort.html)

```markdown

StoogeSort(A,l,r):	
	
1. if A[r] < A[l]		
2. swap A[r] and A[l]		
3. if r - l > 1		
4. t = floor((r - l + 1)/3)		
5. StoogeSort(A,l,r-t)		
6. StoogeSort(A,l+t,r)		
7. StoogeSort(A,l,r-t)
```

 
