# UnderstandingBigO_Notation_Correctly

**(1) A program runs at 1 second per n. How much longer will a program that runs in n^3 take than a program that runs in n^2 if n = 25. (Hint: Answer = Larger n - Smaller n)**

⇒ 25 * 25 * 25 - 25 * 25 

**(2) Which program is overall faster? ⇒ Program A** 

**Program A:**

Load: O(n)

Operate: O(n)

Output: O(n)

**Program B:**

Load: O(1)

Operate: O(1)

Output: O(n^2)

**(3) Which Greek letter is most important for comparing algorithms?**

O(n)

```swift
let dataList = [3, 2, 10, 5] // n = 4 
for data in dataList {
   print(data)
}
```

---

O(n^2)

```swift
for data in dataList {
     for anotherData in anotherDataList {
          if data == anotherData {
						   print(data == anotherData)
          }
     }
}
```
