# Basic msfconsole Commands

## 1. What is the Metasploit prompt?

The prompt tells you you are inside the Metasploit environment.

### Example

```text
msf6 >
```

### Why do we need it?

It helps you know whether you are in the Linux shell or inside `msfconsole`.

### Practice exercise

Open `msfconsole` and write down the prompt you see.

### Common mistakes

- Running shell commands in the wrong environment.
- Forgetting that Metasploit and the Linux shell are different.

### Recap

The prompt tells you where you are.

### Review questions

1. What does the Metasploit prompt look like?
2. Why is the prompt important?
3. What is the difference between a shell and `msfconsole`?

---

## 2. `help`

```text
help
```

This displays the available commands in Metasploit.

### Why do we need it?

It is the fastest way to learn what the console can do.

### Practice exercise

Start `msfconsole` and run `help`.

### Common mistakes

- Skipping `help` and guessing.
- Forgetting that shell commands and Metasploit commands are different.

### Recap

`help` is your built-in guide inside the framework.

### Review questions

1. What does `help` do?
2. Why is it useful for beginners?
3. When should you use it?

---

## 3. `search`

```text
search smb
```

This searches for modules related to a keyword.

### Why do we need it?

It helps you find what you need without guessing the exact module name.

### Simple explanation

`search` is like using a catalog before choosing a tool.

### Practice exercise

Try:

```text
search ssh
search http
```

### Common mistakes

- Searching with vague terms.
- Assuming the first result is the correct choice.

### Recap

`search` helps you locate relevant modules by keyword.

### Review questions

1. What does `search` do?
2. Why is it useful?
3. What is an example of a search term?

---

## 4. `info`

```text
info exploit/windows/smb/ms17_010_eternalblue
```

This shows information about a specific module, including its description and options.

### Why do we need it?

You should understand what a module does before using it.

### Simple explanation

`info` is like reading the manual before using a tool.

### Practice exercise

Use `search` to find a module, then run `info` on it.

### Common mistakes

- Selecting a module without reading it.
- Ignoring required options.

### Recap

`info` explains what the module does and what it requires.

### Review questions

1. What does `info` show?
2. Why is it important before using a module?
3. What does it help you identify?

---

## 5. `use`

```text
use exploit/windows/smb/ms17_010_eternalblue
```

This selects a module so you can inspect and configure it.

### Why do we need it?

Selecting a module does not mean it has been executed.

### Simple explanation

You choose the tool first, then decide how it should be configured.

### Practice exercise

Use a harmless module name and inspect its options.

### Common mistakes

- Thinking `use` automatically runs the exploit.
- Forgetting to inspect `show options` after selecting a module.

### Recap

`use` loads a module; it does not automatically execute it.

### Review questions

1. What does `use` do?
2. Why is it different from executing a module?
3. What should you do after selecting a module?

---

## 6. `show options`

```text
show options
```

This displays the settings required or optional for the selected module.

### Why do we need it?

It tells you what values are required before a module can be used.

### Important values

- `RHOSTS`: the target host or host range.
- `RPORT`: the target port.
- `LHOST`: the local host interface.
- `LPORT`: the local port used for a callback or listener.

### Practice exercise

Select a sample module and run `show options`.

### Recap

`show options` reveals what the module needs before execution.

### Review questions

1. What does `show options` display?
2. What does `RHOSTS` mean?
3. What is the difference between `RHOSTS` and `LHOST`?

---

## 7. `back`

```text
back
```

This exits the current module context and returns to the main Metasploit prompt.

### Why do we need it?

It helps you switch between modules without confusion.

### Practice exercise

Select a module, then run `back` to return to the main console.

### Recap

`back` returns you to the main console.

### Review questions

1. What does `back` do?
2. Why is it useful?
3. When would you use it?

---

## 8. `exit`

```text
exit
```

This exits `msfconsole`.

### Why do we need it?

You need to know how to leave the console cleanly and return to the Linux shell.

### Practice exercise

Open `msfconsole`, then type `exit`.

### Recap

`exit` ends the Metasploit session.

### Review questions

1. What does `exit` do?
2. Why is it important to know how to exit properly?
3. What is the difference between leaving a module and leaving the console?

## Next steps

Continue to [Searching Modules](./searching-modules.md).
