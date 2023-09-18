# Writing good documentation for Github

## Step 1 - Using Codeblocks.

Codeblockes in markdown make it *very easy* for tech people to ***copy, paste, and share*** code. A good __Cloud Engineer__ uses CodeBlock when ever possible.

Because it allows other to copy and past their code to replace or research issues.

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")
```

![github](https://github.com/eyob-berhe/github-docs-example/assets/129125707/ddc30b2a-09d8-4fc2-bf4c-399f7065be3c)


```bash
Treceback (Most recent call last):
    2: from /user/bin/irb:23:in `<main>'
    1: from (irb): 1
RuntimeError: This is a custom error message
```

## Step 3 - Use Github flovoured Markdown Task Lists

Github extends Markdown to have a list where you can check of items

## Referances

- [Gitlab Flavored Markdown Spec](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github)


![Screenshot 2023-07-13 000342](https://github.com/eyob-berhe/github-docs-example/assets/129125707/69d2ca73-4016-49ca-ace0-8f9780192066)


- CodeSnipped screenshot

![Screenshot 2023-04-25 014318](https://github.com/eyob-berhe/github-docs-example/assets/129125707/edf9d81a-5a7f-40c5-9b7c-8c6255ce8c40)
