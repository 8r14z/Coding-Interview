# Coding Interview
All coding problems I have ever met so far when taking coding interview

# Table of content:
1. [Find intersection of 2 arrays](#p1)
2. [Find anagrams](#p2)
3. [Remove duplicates in string](#p3)
4. [2-sum](#p4)


### <a name="p1"/>1. Find intersection between 2 arrays
Write a function with input of 2 arrays and return another array contain all intersection between them.
#### 1.1 Arrays are sorted
```swift
let array1 = [1,3,5,10,13]
let array2 = [1,5,9,10,15]
// output = [1,5,10]
```
#### 1.2 Arrays are not sorted
```swift 
let array1 = [4,2,5,1,7]
let array2 = [7,2,6,8,1]
// output = [7,2,1]
```

### <a name="p2"/>2. Find anagrams in array
Find all anagrams in input array and return all set of anagrams
```swift
// "alee" - "eale" => anagrams
// "ale" - "eeal" => not 
// "ale" - "e a l" => anagrams

let input = ["pear", "amleth", "dormitory", "tinsel", "dirty room", "hamlet", "listen", "silnet"
// output = ["amleth,hamlet", "dirty room,dormitory", "listen,silnet,tinsel", "pear"] // order is not considered
```

### <a name="p3"/>3. Remove duplicated characters in string
Remove all duplicated characterd in a string and return another string
```swift
let input = "abbdcde"
// output = "abdce"
```

### <a name="p4"/>4. 2-sum problem
Give input of array, find a pair of indexes make sum equal to `K`
#### 4.1 Array is sorted
```swift
let input = [1,4,5,8,10]
let k = 9
// output = [0, 8]
```

#### 4.2 Array is not sorted
```swift
let input = [2,5,1,6,9]
let k = 3
// output = [0,2]
```
