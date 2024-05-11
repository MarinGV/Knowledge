# Syntax

The syntax used is: `` ` `` 

Example:
```sh
`backtick`
```

Output: `backtick`

---

### Escaping Backticks

If you want to denote a backtick as code then use more.

Example:
```sh
``Used more `backticks` at the start and beginning.``
```

Output: ``Used more `backticks` at the start and beginning.``

---

### Fenced Code Block

If you want to make a code block

Example:
````sh
```
Creating
a code block
by surrounding it 
at the top and bottom
by a 'fence' of backticks.
Minimum 3 are required.
```
````
Output:
```
Creating
a code block
by surrounding it 
at the top and bottom
by a 'fence' of backticks.
Minimum 3 are required.
```

---

### Syntax Highlighting

If you want to highlight stuff inside code blocks, specify a language beside the top fence.

Example:
````sh
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
````
Output:
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```