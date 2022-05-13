[16,21,11,8,12,22] -> Merge Sort
--

  1- Write the steps of the merge sort for the given series.
  --
  

       [16][21][11]           [8][12][22]
           /     \               /       \
     [16][21]    [11]          [8][12]    [22]
       / \        \            /   \        \    
    [16] [21]    [11]        [8]  [12]     [22]
        \        /               \         /      
      [11][16][21]             [8][12][22]
            \                     /    
            [8][11][12][16][21][22]

2- Write the Big-O notation.
--
	Every split application has the (n-1) time complexity. And beacuse of the splitting to 2 in each step until one data at a time, we can consider the total split number as a x; we can consider the total number of data as n.
	2^x=n
	x=log(n) 
	log(n)*(n-1)
	so, the Big-O notation is O(n*log(n))
