---
description: >-
  This page contains the instructions for problem one  in our Introduction to
  C++ lesson.
---

# 🧮 Problem 1: Odd or Even?

### 📋 Description 

This program asks the user to enter a number, determines whether that number is even or odd, and then prints a message to the user telling them the answer. 

For example, if the user enters 3, the program should print something like "The number you entered is odd!".

So how can we determine whether a number is even or odd? We can use a new operator called **modulus** that will help us calculate the remainder! Remember that when we divide an even number by **2**, the remainder is **0**, so we can use modulus to check what the remainder is. If it's **0**, the number is even. Otherwise, the number is odd!

If we have a variable called x and we want to use modulus to check what the remainder is when it's divided by **2**, it will look like this:

```cpp
if(x % 2 == 0){
    // the remainder of x divided by 2 is 0
    // so it's even!
}else{
    // the remainder is NOT 0
    // so it must be odd!
}
```

### 📝 Template Links 

Like last week, you can choose to use `iostream` \(`cin` and `cout`\) or `stdio` \(`printf` and `scanf`\). The links to templates for both are below.

* Here is the `iostream` [template](https://cplayground.com/?p=bee-salmon-albatross) 
* Here is the `stdio`[template](https://cplayground.com/?p=finch-polar-quetzal)

