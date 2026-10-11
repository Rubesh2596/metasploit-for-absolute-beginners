# Understanding Metasploit Options

## 1. What are required and optional options?

When you select a module, it may have required options and optional settings.

### Why do we need it?

You need to know what must be set before the module can be used meaningfully.

### Simple explanation

Required options are like required fields in a form. Optional ones are extra settings that might help.

### Example

A module might require:

- `RHOSTS`
- `RPORT`

and optionally allow values like:

- `SSL`
- `VERBOSE`

### Practice exercise

Select a module and run:

```text
show options
```

### Recap

Options explain what the module needs and what it can adjust.

### Review questions

1. What is a required option?
2. What is an optional option?
3. Why do you need to inspect them?

---

## 2. Meaning of important values

### `RHOSTS`
The remote host or host range that the module will target.

### `RPORT`
The target port the service listens on.

### `LHOST`
The local host interface or machine that is part of the connection.

### `LPORT`
The local port used for a callback or listener.

### Why do we need it?

These values describe the relationship between the machine running the tool and the target environment.

### Practice exercise

Look at a module and identify `RHOSTS`, `RPORT`, `LHOST`, and `LPORT`.

### Common mistakes

- Confusing the local and remote sides.
- Assuming the target is always the machine running the tool.

### Recap

The option names describe the communication path between the lab machine and the target.

### Review questions

1. What does `RHOSTS` mean?
2. What does `RPORT` mean?
3. What is the difference between `LHOST` and `RHOSTS`?

---

## 3. How to inspect options without executing a module

Before running a module, inspect its options with:

```text
show options
```

### Why do we need it?

You are learning to check requirements and understand the module before using it.

### Simple explanation

This is like reviewing a checklist before starting a task.

### Practice exercise

Choose a harmless module and inspect its `show options` output.

### Recap

Inspecting options is a safe and responsible habit.

### Review questions

1. What command shows module options?
2. Why do we inspect them before execution?
3. Why is this a good habit for beginners?

## Next steps

Continue to [Exploit Modules](../06-metasploit-modules/exploits.md).
