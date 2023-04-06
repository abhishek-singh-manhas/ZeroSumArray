
<div align = "center">

![image](https://github.com/abhishek-singh-manhas/ZeroSumArray/blob/78cad99d61a767ad197e66c5e5788217abfb96e9/Screenshots/head.png)

</div>



# Zero Sum Array

In this program, we first check if the array contains any zero element. If yes, then we add that element to the result list and return it.
Otherwise, we maintain a HashMap to keep track of the sum of elements encountered so far and their indices. We iterate through the array and at each iteration,
we calculate the sum of elements encountered so far. If the sum is zero, then we add all the elements from the beginning of the array to the current index to 
the result list and return it. If the sum has already been encountered before, then we add all the elements from the index after the last occurrence of the sum
to the current index to the result list and return it. If no such combination of elements is found whose sum is zero, then we return an empty list.


### > ```IDE Used: ItelliJ IDEA```
### > ```Programming Language: JAVA 17```


### Output Screenshots

![image](https://github.com/abhishek-singh-manhas/ZeroSumArray/blob/eee7506265a831fd557021a6f69befe7d0ec5be3/Screenshots/snap1.jpg)
![image](https://github.com/abhishek-singh-manhas/ZeroSumArray/blob/eee7506265a831fd557021a6f69befe7d0ec5be3/Screenshots/snap2.jpg)
