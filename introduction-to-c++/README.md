---
description: >-
  This page contains the materials and instructions that we used to introduce
  the students to programming in C++.
---

# 🐱‍💻Introduction to C++

### 👩‍💻 Coding Activity

The goal of this activity is to introduce and play with the C++ language.

In `C++`, there are two ways we can do input and output: using the `stdio` library \(`printf` and `scanf`\) and using the `iostream` library \(`cin` and `cout`\). Below is an example of what each version looks like:

#### 🌈 Stdio \(printf / scanf\)

```cpp
// declare variable to hold user input
int x;

// print a statement asking user to enter a number
printf("Please enter a number: ");

// read in the user input (the %d means we expect an int)
// and put it into the variable x
scanf("%d", &x);

// print what the user entered back to them 
// (%d is a placeholder for the int we want to print, \n means print a new line)
printf("You entered: %d \n", x);
```

As you can see, the syntax for `printf` and `scanf` looks a little bit tricky to get the hang of, but we can help out!

#### ⛅ Iostream \(cin / cout\)

```cpp
// declare variable to hold user input
int x;

// print a statement prompting the user for input
cout << "Please enter a number: ";

// read in the user input and store it in the variable x
cin >> x;

// print what the user entered back to them (endl means print a new line)
cout << "You entered: " << x << endl;
```

The syntax for`cin`and`cout`is easier to learn, but`ostream`can give you some weird-looking error messages! Let us know if you run into this and we can help.

For each example and solution in this activity, we have a version for `stdio` and `iostream`. When you're working on the activities below, you can choose to use whichever you and your group prefer!

