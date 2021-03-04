# Algorithm to Write an array of with Integers of length 6

1. from an unsorted array of x={5,9,7,6,4,3}
2. Compare with first two elements to check which one is greater.
3. is 5>9,if false, retain the initial array settings,otherwise swap number positions.
4. output x = {5,9,7,6,4,3}
5. move to next array item for comparism
6. is 9>7, repeat steps 3,4 & 5
7. Finally, once array elements are well sorted and swapping cannot be done, terminate process.

# Algorithm Bubble_Sort(list) {6,5,4,3,2,1)
1.  Pre: list != fi
2.  Post: list is sorted in ascending order for all values
3.  for i <- 0 to list:Count - 1
4.  for j <- 0 to list:Count - 1
5.  if list[i] < list[j]
6.  Swap(list[i]; list[j])
7.  end if
8.  end for
9.  end for
10. return list {5,4,3,2,1,6}
11. end Bubble_Sort 
