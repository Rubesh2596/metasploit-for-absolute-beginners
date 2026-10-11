# Searching Modules in Metasploit

## 1. Why searching matters

Metasploit contains many modules. A search command helps you narrow the list.

### Why do we need it?

It helps you avoid guessing and lets you inspect the right module family.

### Simple explanation

Searching is like looking through a catalog before choosing a book.

### Command example

```text
search smb
```

### Practice exercise

Try:

```text
search ssh
search http
search scanner
```

### Common mistakes

- Searching too broadly without understanding the result.
- Assuming the first result is always the correct one.

### Recap

Search helps you find relevant modules before you use them.

### Review questions

1. What does `search` help you do?
2. Why is it important before selecting a module?
3. Name one search term you could use.

---

## 2. Reading module descriptions

A module description explains what it does and when it is relevant.

### Why do we need it?

Descriptions help you understand the module before configuring it.

### Example

A result might describe a module as an exploit, scanner, or auxiliary tool.

### Practice exercise

Search for a module and read the description before doing anything else.

### Recap

Descriptions are the first clue for understanding whether a module matches your goal.

### Review questions

1. Why is the description important?
2. What should you read before selecting a module?
3. Why is this a safe habit?

---

## 3. Module paths

Modules often have a path such as:

```text
exploit/windows/smb/ms17_010_eternalblue
```

### Why do we need it?

The path gives you a clue about the module family and target category.

### Simple explanation

The path tells you what kind of module it is and what technology it relates to.

### Practice exercise

Read a few module paths and identify the module family.

### Recap

Module paths help categorize modules and explain their purpose.

### Review questions

1. What is a module path?
2. Why is categorization useful?
3. What does the path usually reveal?

## Next steps

Continue to [Understanding Options](./understanding-options.md).
