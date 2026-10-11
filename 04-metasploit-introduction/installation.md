# Installing Metasploit

## 1. How to check whether Metasploit is installed

A beginner should first verify whether the tool is already available.

### Command

```bash
msfconsole --version
```

### Why do we need it?

This is the quickest way to confirm whether Metasploit is installed.

### Example output

```text
Framework: 6.x
Console  : 6.x
```

The exact version may vary.

### Practice exercise

Run the version check in your Kali terminal.

### Common mistakes

- Installing without checking.
- Assuming the command will work because a tutorial mentioned it.

### Recap

Check first; install only when necessary.

### Review questions

1. What is the command to check Metasploit version?
2. Why is checking first useful?
3. What might the output look like?

---

## 2. Installing Metasploit on Kali

If the tool is not installed, update packages and install the package.

### Commands

```bash
sudo apt update
sudo apt install metasploit-framework -y
```

### Why do we need it?

The package manager prepares the system and installs the tool.

### Simple explanation

Kali often already includes Metasploit. Avoid reinstalling unless needed.

### Practice exercise

Check the system status and decide whether you need to install it.

### Recap

Installation should be targeted and deliberate.

### Review questions

1. What does `sudo apt update` do?
2. What package may be installed for Metasploit?
3. Why should beginners avoid unnecessary reinstallations?

## Next steps

Continue to [Starting msfconsole](./starting-msfconsole.md).
