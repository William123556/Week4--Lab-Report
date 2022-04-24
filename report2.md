# Week4--Lab-Report
<img width="1382" alt="Screen Shot 2022-04-23 at 5 31 52 PM" src="https://user-images.githubusercontent.com/103155832/164950666-acd2dde4-b857-4fab-a037-63385ca29dcd.png">

<img width="1311" alt="Screen Shot 2022-04-23 at 5 36 11 PM" src="https://user-images.githubusercontent.com/103155832/164950726-e5e27b08-3234-4a05-9ba3-f5aff633e5f2.png">

The last index should be one less than the current length, so to fix this, we needed to add a minus one to the markdown length. 

**breaking test 1**
<img width="1272" alt="Screen Shot 2022-04-23 at 5 38 18 PM" src="https://user-images.githubusercontent.com/103155832/164950778-4e7d1561-8422-4794-a4ad-e4b7a031d268.png">

**breaking test 1 output**

<img width="737" alt="Screen Shot 2022-04-23 at 6 19 57 PM" src="https://user-images.githubusercontent.com/103155832/164951615-a69d83ed-6539-48a6-83f4-d3d34c8d4138.png">

**test file**
https://github.com/TuannDang/markdown-parser/blob/main/testfile2.md

**Fix 1**
<img width="1312" alt="Screen Shot 2022-04-23 at 5 39 21 PM" src="https://user-images.githubusercontent.com/103155832/164950790-17a2da2e-b604-4a59-994e-d57a4a1ac305.png">

One technique I used was to just read over the program to see what it does and what each line of code is supposed to do. I just made changes incrementally until it did what I wanted. After looking at what the indexOf() method does I was able to come up with an easy and straightforward solution.

**breaking test 2**
<img width="1202" alt="Screen Shot 2022-04-23 at 5 40 04 PM" src="https://user-images.githubusercontent.com/103155832/164950808-1645ce3e-dd81-4c3e-910b-63c8777692fa.png">

**fix 2**
<img width="1079" alt="Screen Shot 2022-04-23 at 5 40 54 PM" src="https://user-images.githubusercontent.com/103155832/164950831-60d0a2a3-d390-4bd8-a2ed-1fe4757cb92d.png">

Added an if statement to check that a parenthesis directly follows the close bracket before appending to the list. 
I only used print statements at first to figure out the index where the parentheses are at. 
