---
{"dg-publish":true,"permalink":"/basics/maths/","tags":["Basics"],"dg-note-properties":{"order":"3","tags":["Basics"]}}
---

Let's do some maths. Open an empty file, maybe `maths.py` or similar and let's print one plus one.
There's a few ways of doing that, can you figure all of them?

> [!question] Task
> Find all three variations of writing `1 + 1`
> > [!info]- Options
> > ```Python
> > print(1 + 1)
> > print("1" + "1")
> > print("1 + 1")
> > ```
> > ### All of these will give you different results upon executing them:
> > The first one is the way of getting the mathematical result, we add both whole numbers, we call these [[Data Types/Integer\|Integers]], and we get , two.
> > The second for some reason returns `11`, why is that? For that, we have to understand, that everything wrapped into a pair of, either single, or double quotation marks counts as a [[Data Types/String\|String]]. Strings are a group of, for Python, unnamed characters; and Python supports the addition of two Strings, `a` and `b`, to create a String of `a` followed by `b`. So Python interprets this as `"1"` followed by `"1"`.
> > And the last one, `"1 + 1"` is, again, a String, so it will print as such.

There are four basic maths operations including the plus:
- `+` Addition
- `-` Subtraction
- `*` Multiplication
- `/` Division

> [!important]
> Be aware division always returns a decimal number, a [[Data Types/Floating Point\|Floating Point]], even if it's `.0`. This does not affect any calculations, it is purely esthetic.

Additionally, powers are represented as `base ** power` and the modulo, the operation to get the remainder, as ` Divident % Divider`.

> [!question] Task
> Now try printing 6 divided by 4 and in another print statement taking the modulo of them.
> > [!check]-
> > ```Python
> > print(6 / 4)
> > print(6 % 4)
> > ```
> > The result of executing it:
> > ```Bash
> > $ python3 ./Python/maths.py
> > 1.5
> > 2
> > ```



---
[[Basics/First lines of code\|Previous]]<span style="float:right">[[Basics/Variables\|Next]]</span>