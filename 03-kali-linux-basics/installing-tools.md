# Installing Tools on Kali Linux

## 1. Why tool installation matters

A learner needs the right tools to practice cybersecurity concepts safely.

### Why do we need it?

Proper tools help you inspect systems, read documentation, and experiment in a controlled environment.

### Simple explanation

Installing tools is like setting up a toolkit before you start a project.

### Example

```bash
sudo apt update
sudo apt install msfconsole -y
```

### Important rule

Only install tools you need, and only in a safe environment.

### Practice exercise

Check whether a tool is already installed before trying to install it again.

### Common mistakes

- Installing without understanding the package.
- Running system changes without reading the command.

### Recap

Tool installation should be deliberate and purposeful.

### Review questions

1. Why is installing tools important?
2. What command updates the package list?
3. What is one safe habit before installing software?

---

## 2. Installing Metasploit on Kali Linux

Metasploit is often already present on Kali, but you should check before reinstalling.

### Check installation

```bash
msfconsole --version
```

If it returns a version, the tool is available.

### If it is not installed

```bash
sudo apt update
sudo apt install metasploit-framework -y
```

### Why do we need it?

You need Metasploit installed before you start learning its console and modules.

### Simple explanation

Do not reinstall anything without first checking whether it is already installed.

### Practice exercise

Run the version command above and decide whether installation is necessary.

### Recap

Check first, then install only if needed.

### Review questions

1. How can you check if Metasploit is installed?
2. Why is checking first a good habit?
3. What does `apt install` do here?

## Next steps

Continue to [What Is Metasploit?](../04-metasploit-introduction/what-is-metasploit.md).
