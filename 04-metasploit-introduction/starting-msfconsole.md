# Starting msfconsole

## 1. How to start Metasploit

Open a regular Kali terminal and type:

```bash
msfconsole
```

### Why do we need it?

This starts the Metasploit command-line interface.

### Simple explanation

When you start Metasploit, you leave the normal Linux shell and enter the Metasploit console.

### Example prompt

```text
msf6 >
```

The command prompt changes from a standard shell prompt to the Metasploit prompt.

### Example shell prompt

```text
kali@kali:~$
```

### Practice exercise

Start `msfconsole` and note how the prompt changes.

### Common mistakes

- Confusing the shell prompt with the Metasploit prompt.
- Running shell commands while still in `msfconsole`.

### Recap

`msfconsole` changes your environment from a Linux shell to the Metasploit console.

### Review questions

1. What command starts Metasploit?
2. What does the Metasploit prompt look like?
3. Why is the prompt important?

---

## 2. Basic help and exit commands

Inside Metasploit, type:

```text
help
```

This shows available commands.

To leave the console, type:

```text
exit
```

### Why do we need it?

You need to know how to leave the console cleanly and understand the prompt difference.

### Practice exercise

Open `msfconsole`, run `help`, and then type `exit`.

### Recap

`help` shows available commands, and `exit` leaves Metasploit.

### Review questions

1. What does `help` do?
2. What command exits Metasploit?
3. Why is it important to know the prompt difference?

## Next steps

Continue to [Basic Commands](../05-learning-msfconsole/basic-commands.md).
