## Sorting Algorithms [![](https://img.shields.io/badge/ChandraMouli-R-orange.svg)](https://github.com/zcam007)[![](https://img.shields.io/github/license/sourcerer-io/hall-of-fame.svg?colorB=ff0000)](https://github.com/zcam007/Sorting-Visualization/blob/master/LICENSE.txt)
This code helps you to understand the different Sorting algorithms. The sorting algorithms depicted in this code are:
1) Bubble Sort
2) Selection Sort
3) Insertion Sort
4) Quick Sort
5) Merge Sort

### Sourcerer
<a href="https://sourcerer.io/zcam007"><img src="https://sourcerer.io/icons/logo-sharing.svg" height="48px"  alt="Sourcerer"></a>
<a href="https://sourcerer.io/zcam007"><img src="https://img.shields.io/badge/JavaScript-154%20commits-orange.svg" alt=""></a>

### Code Requirements
The example code is in Java ([version 1.8](https://java.com/en/download/) or higher will work).

### Description
A sorting algorithm is an algorithm made up of a series of instructions that takes an array as input, performs specified operations on the array, sometimes called a list, and outputs a sorted array.
 Efficient sorting is important for optimizing the use of other algorithms (such as search and merge algorithms) which require input data to be in sorted lists; it is also often useful for canonicalizing data and for producing human-readable output. More formally, the output must satisfy two conditions:

    The output is in nondecreasing order.
    The output is a permutation (reordering) of the input.

<img src="https://github.com/zcam007/Sorting-Visualization/blob/master/sort.gif">


```java

switch(ch)
		{
			case 1:
				BinarySort(a,n);
				break;
			case 2:
				SelectionSort(a,n);
				break;
			case 3:
				InsertionSort(a,n);
				break;
			case 4:
				int start=0;
				int end=n-1;
				QuickSort(a,start,end);
				print(a,n);
				break;
			case 5:
				MergeSort(a,n);
				print(a,n);
				break;
		}
```


You can select any algorithm from the list and then enter an array which would get sorted through the selected algorithm.


### Execution
To compile the code, simply run the `javac Sort.java`.
To run the code, type `java Sort`

```
javac Sort.java
java Sort
```
