# 🎉 Problem 4: More Functions!

### Description 📋

In this program, we're going to play more with functions! But this time, we're going to pass our function some information it can do stuff with and then our function can give us back some information. The things we pass to our functions are called **parameters** and the thing our function gives back to us is called a **return value**.

You might remember an example from last week where our program asked the user to enter two numbers, added them together, and then printed the sum to the user. We're going to do this same thing in this program, but we're going to use a function to do the adding! 

**We are going to going to:**

* pass the function two numbers
  * The function will add them together
  * Then the function will return the sum
* We will then print the result of calling the function

You might have noticed in the last problem that the word `void` was sometimes in front of the function name. This was to specify that the function wasn't returning anything. In this program, we want to return the sum so we'll replace `void` with the data type we want to return, which is an `int`. We don't need the data type when we're calling the function though! When our function returns a value, we'll need to declare a variable to hold the value it returns.

You also might have noticed some empty brackets \(\) next to the function name in the last example. Inside those brackets is where we'll put our **parameters**!

If the variables holding the values we want to pass as parameters were c and d, and the function's name was `add`, calling the function would look like:

```text
int sum = add(c, d);
```

It might seem a little bit confusing now, but it should start to make sense when you start playing with this program. We can help if it's confusing!

### Template Links 📝

Templates for `iostream` \(`cin` and `cout`\) and `stdio` \(`scanf` and `printf`\) are below.

* Here is the `iostream` [template](https://cplayground.com/?p=pig-goldfinch-echidna)
* Here is the `stdio` [template](https://cplayground.com/?p=wolf-kangaroo-locust)

