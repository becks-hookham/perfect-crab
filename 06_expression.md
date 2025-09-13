# Expressions
[Vimeo]( https://vimeo.com/954334376/0c486313d0#t=0)

## What is an Expression?

An **expression** is a piece of code that produces a value.  
It can be made up of:
- **Literals** (like `5` or `"hello"`)
- **Variables** (like `x` or `name`)
- **Operators** (like `+`, `-`, `*`, `/`)
- **Function calls** (like `len("hi")`)

##  Examples

- `2 + 3` → evaluates to `5`
- `"hi" + " there"` → evaluates to `"hi there"`
- `x * 4` → if `x = 2`, this evaluates to `8`
- `len("cat")` → evaluates to `3`

👉 The important thing is:  
An expression is **anything in your code that Python can figure out and turn into a value**.

# Expression vs Statement

## Expression
- An **expression** is code that produces a **value**.  
- It can be used inside other code.  
- Examples:
  - `2 + 3` → gives `5`
  - `"hi".upper()` → gives `"HI"`
  - `x * 4` → gives some number, depending on `x`

👉 Expressions **return something**.

---

## Statement
- A **statement** is code that **does something**.  
- It usually controls the flow of the program or makes Python take an action.  
- Examples:
  - `x = 5` → assignment statement (stores a value in `x`)
  - `if x > 0:` → if statement (controls code execution)
  - `for i in range(3):` → loop statement

👉 Statements **don’t return a value directly** — they make something happen.

---

## Quick way to remember
- **Expression** → “Gives me a value.”  
- **Statement** → “Makes something happen.”

