---
{"dg-publish":true,"permalink":"/basics/if-statements/","tags":["Basics"],"dg-note-properties":{"order":"5","tags":["Basics"]}}
---

Sometimes you need to check, if an expression is true and act upon it
That's what if-statements can be used for
To initiate a comparison, write `if`, followed by one of these possible comparators, ending the line with a colon. Any line of code written with an indent after the colon will only be executed if the condition is true. 
Additionally, if you want to check another condition it is possible to use `elif` with the same structure as `if`, it will only trigger if the beforehand used `if` returned as `False`. Lastly it is possible to create a fallback, using `else`, it accepts no condition and all else returned false.
##### Possible operators
- `<` less than
- `<=` less than or equal to
- `==` equal to
- `>=` bigger than or equal to
- `>` bigger than
- `in` an element is part of an iterable

> [!important] Booleans
> All operators listed above return a [[Data Types/Boolean\|Boolean]] value, a binary `True`, or `False`.

> [!question] Task
> Create a program that uses a variable, for example `number` and give it an Integer value. If the value is is above five, print `> 5`, otherwise `<= 5`
> > [!check]-
> > ```Python
> > number = 5
> > if number > 5:
> > 	print("> 5")
> > else:
> > 	print("<= 5")
> > ```



---
[[Basics/Variables\|Previous]]<span style="float:right">[[Basics/Calculator\|Next]]</span>