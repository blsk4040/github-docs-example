# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste,share code**.

A good **_Cloud Engineer_** uses Codeblocks whenever possible.

Because it allows others to copy and paste thier code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks ( ` ).
- Do not use single quotation ( ''' )


# Define a Variable

```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Input a number from the user
num = int(input("Enter a non-negative integer: "))

if num < 0:
    print("Factorial is not defined for negative numbers.")
else:
    result = factorial(num)
    print(f"The factorial of {num} is {result}")

```

- Same code but this time with colour in .

```python

def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Input a number from the user
num = int(input("Enter a non-negative integer: "))

if num < 0:
    print("Factorial is not defined for negative numbers.")
else:
    result = factorial(num)
    print(f"The factorial of {num} is {result}")
```
- Upload image into github.
  
**_Just drag and paste the image here....._**

    
![download](https://github.com/blsk4040/github-docs-example/assets/141501109/836c492c-ab04-429c-92f8-9314a867bc0f)



Good Cloud Engineers use codeblocks for both Code and Erros that appaers in the console.



```bash
Traceback (most recent call last):
  File "sample.py", line 5, in <module>
    result = 10 / 0
ZeroDivisionError: division by zero
```
>Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavoured Markdown Task Lists
Github extends Markdown to have a list where you can offer items. [<sup>[1]
</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3


# Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emoji shortcode.
Some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud |`:cloud:` | :cloud: |
| Cloud with lighting |`:cloud with lighting` | 🌩️ |

# Step 5 - How to create a table

You can do the folowing markdown formart to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud |`:cloud:` | :cloud: |
| Cloud with lighting |`:cloud with lighting` | 🌩️ |
```
Github extends the functionality tables to provide more aligment and table cell formatting option. [<sup>[2]
</sup>](#external-references)



##External  References 

-[GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

-[Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

-[GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)

-[GFM - Table (with extension)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
