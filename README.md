# Using the dc calculator
**========================**

The 'dc' program is a calculaotr app. It supports a variety of 
calculations including:
According to the "manual page" or man page" on Unix: the dc calculator is:

> 'dc'(1) is a command line desk calc app. 
> It uses a reverse polish notation number, where it is stored in a
> stack and the user opertaers te calculations.

* add
* subtract
* multiply
* divide
Can add asterisks to create bullet points
To use a reverse polish calculator, you enter the numbers first
and then the operation.
For example, to multiply the numbers 6 and 7,
you would do this:


1. Enter 'c' clear the memory.
1. Enter the number '6'
2. Enter the number '7'
3. Enter an * to multiply 
4. Enter 'p' to print the result

Here's a sample 'dc'session that multiplies 6 and 7:


''''
c
6
7
*
p
42
```
blocking = fills rectangle
And that's how your calculate with 'dc'.
