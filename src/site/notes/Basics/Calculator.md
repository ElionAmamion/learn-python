---
{"dg-publish":true,"permalink":"/basics/calculator/","tags":["Basics","Project"],"dg-note-properties":{"order":"6","tags":["Basics","Project"]}}
---

This will be your first Project.
A project is a test, where you apply the previously learned material and create a working application or similar in multiple phases which each can have a few extra infos needed.
The current Project will be a working 2 expression calculator running in your console.
## Phase one
For this we will need to learn one more tool, which will allow us to accept user input: [[Functions/input()\|input()]].
It allows us to wait until the user types something into the terminal and then store this value in a Variable. For our purposes we need the input to be an Integer, but the input function only returns a String. To circumvent that, we can use _type casting_, which means we take the input and turn it into an Integer: `int(input())`.

> [!question] Task
> Create a program, which takes in two numbers and returns the added result
> > [!check]-
> > ```Python
> > num1 = int(input())
> > num2 = int(input())
> > print(num1 + num2)
> > ```

## Phase two
This Phase focuses on implementing different operations.
To differentiate between them, we will have to compare them using [[Basics/if-statements\|if-statements]].

> [!question] Task
> Modify your last program, so that there is a third input, which accepts any of the operations and returns a processed output
> > [!check]-
> > ```Python
> > num1 = int(input())
> > operator = input()
> > num2 = int(input())
> > if operator == "+":
> > 	print(num1 + num2)
> > elif operator == "-":
> > 	print(num1 - num2)
> > elif operator == "*":
> > 	print(num1 * num2)
> > else:
> > 	print(num1 / num2)
> > ```

You have succesfully completed your first project and the _**Basics**_ section of this Vault. Congratulations!



---
[[Basics/if-statements\|Previous]]<span style="float:right">Comming soon</span>