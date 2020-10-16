## Algorithm Visualization:
### Sorting Algorithms:

[insertion Sort:](http://rosulek.github.io/vamonos/demos/insertion_sort.html)
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

[Selection Sort:](http://rosulek.github.io/vamonos/demos/selection_sort.html)
```markdown

SelectionSort(A):
1. for i = 0 to A.length-2 /find smallest item in A[i..]		
2. m = i		
3. for j = i+1 to A.length-1		
4. if A[j] < A[m]		
5. m = j		
6. swap A[i] and A[j]

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/anisurrahmanlikhon/Sorting-Algorithms/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
