# PCS2-3rd-Assignment
In this assignment, We want to compare 4 different algorithms to see how they work
in a matter of time. we want to compare all these algorithms to understand which works faster but at first,
we have to visualize each of them in different plot to see the details. firts, we should write a function to add a random element to the list, then write a function to get the minimum, and at the end, get the maximum value of the list.




first of all, in the plot below, we see that how quick sort works when we add elements to the list. When the list is getting bigger, quick sort becomes slower. we know for example, when we have one elements which the function initiates like that, it takes no time to get min and get max so its immediately. but after the add function which add after and after, it is getting slower because
obviously, its harder to sort 10 numbers in compare to 3 numbers for instance.

here is the plot of how quick sort works


<p align="center"><img src = "https://github.com/aminnoorani/plots/blob/master/quicksort2.png" width = "600" height = "400"/>


then we comes to Bubble sort,which is similar quick sort.

<p align="center"><img src = "https://github.com/aminnoorani/plots/blob/master/bubblesort4.png" width = "600" height = "400"/>

it is same as quick sort, it gets slower when the number of elements are increasing as sorting more numbers, is more difficult!


A binary tree is made of nodes, where each node contains a left pointer, a right pointer, and a data element. The root pointer points to the topmost node in the tree. The left and right pointers recursively point to smaller subtrees on either side.
it is similar to heap sort, which is dependent on size of the element. you can see how it works below:



<p align="center"><img src = "https://github.com/aminnoorani/plots/blob/master/binarytree1.png" width = "500" height = "500"/>









below is the plot of heap sort, 
this is asorting algorithm that works by first organizing the data to be sorted into a special type of binary tree called a heap. so it is not clear that how it works, performance of heap sort is dependent on the size of inserted elements and the previous branches. the different between heap sort and binary tree, it starts from bottom, there is no left or right pointer so it is much more faster



<p align="center"><img src = "https://github.com/aminnoorani/plots/blob/master/Heapsort3.png" width = "500" height = "500"/>








Now we found out that how all algorithms works and how much they take time when the number of elements are increasing.
we are giving it lists with lengths starting from 100 going up to 1000 with 100 steps. As it is illustrated in the plot below, bubble sort has major difference in compare to others. 



<p align="center"><img src = "https://github.com/aminnoorani/plots/blob/master/compadds5.png" width = "500" height = "500"/>




and then, we want to compare the same issue with get_min and get_max functions which we see signifacnt differences between binary tree  and the rest. but mainly we should compare heap and binary tree because the other two are similar to each other and these two(binary tree and heap) are alike. so here they are:



<p align="center"><img src = "https://github.com/aminnoorani/plots/blob/master/comgetmin6.png" width = "400" height = "350"/>
  
  
  
  
  
  
  
  
  
  <img src = "https://github.com/aminnoorani/plots/blob/master/compgetmax7.png" width = "400" height = "350"/>












