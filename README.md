[22,27,16,2,18,6] -> Insertion Sort:
1. [22,27,16,2,18,6] -- (n)
2. [2,27,16,22,18,6] -- (n-1)
3. [2,6,16,22,18,27] -- (n-2)
4. [2,6,16,18,22,27] -- (n-3)
Big-O Notation = O(n^2) 
Time Complexity:
Best case: Aradığımız sayının en başta olması demektir. Best case = O(n)
Avarage case: Aradığımız sayının ortada olması demektir. Avarage case= O(n^2)
Worst case: Aradığımız sayının en sonda olması demektir. Worst casse = O(n^2)
=> 18 sayısı dizi sıralandığında ortada bulunduğu için avarage case kapsamına girer.
Insertion Sort'a göre  [7,3,5,8,2,9,4,15,6] ilk 4 adımı:
1. [2,3,5,8,7,9,4,15,6]  
2. [2,3,4,8,7,9,5,15,6] 
3. [2,3,4,5,7,9,8,15,6] 
4. [2,3,4,5,6,9,8,15,7] 
