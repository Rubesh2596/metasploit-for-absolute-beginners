# Kali Linux Terminal Commands

## 1. What is Kali Linux?

Kali Linux is a Linux distribution built for security work, learning, and digital forensics.

### Why do we need it?

It includes many tools useful for learning cybersecurity in a controlled environment.

### Simple explanation

Kali is like a toolkit for cybersecurity students.

### Important terminology

- Distribution: a version of Linux with a chosen set of tools.
- Terminal: the command-line interface.

### Practice exercise

Open a terminal and type:

```bash
whoami
```

This tells you which user you are using.

### Common mistakes

- Running destructive commands without understanding them.
- Assuming every Linux system is the same.

### Recap

Kali Linux is a security-focused Linux distribution.

### Review questions

1. What is Kali Linux?
2. Why do people use it?
3. What is a terminal?

---

## 2. Current working directory

The current working directory is the folder you are currently inside.

### Why do we need it?

It tells you where commands will run and where files are located.

### Command example

```bash
pwd
```

`pwd` means “print working directory.”

### Practice exercise

Run `pwd` and write down the output.

### Recap

`pwd` shows the current directory.

### Review questions

1. What does `pwd` do?
2. Why is it important?
3. What is a working directory?

---

## 3. Absolute vs. relative paths

### Absolute path
A full path starting from the root of the filesystem, for example:

```bash
/home/kali/projects
```

### Relative path
A path that is relative to your current location, for example:

```bash
./notes.txt
```

### Example

```bash
cd /home/kali
```

### Practice exercise

Try `pwd` and `ls` to see how your location affects relative paths.

### Recap

Absolute paths are complete; relative paths depend on your current folder.

### Review questions

1. What is an absolute path?
2. What is a relative path?
3. Why does your current directory matter?

---

## 4. Common commands

### `ls`
List files and folders.

```bash
ls
```

### `cd`
Change directory.

```bash
cd /home/kali
```

### `mkdir`
Create a folder.

```bash
mkdir practice-lab
```

### `touch`
Create an empty file.

```bash
touch notes.txt
```

### `cat`
Display file content.

```bash
cat notes.txt
```

### `less`
View a file one screen at a time.

```bash
less notes.txt
```

### `cp`
Copy a file.

```bash
cp notes.txt backup.txt
```

### `mv`
Move or rename a file.

```bash
mv notes.txt archived/notes.txt
```

### `rm`
Remove a file.

```bash
rm notes.txt
```

### Warning

`rm` is destructive. Use it carefully and only when you know what you are deleting.

### `find`
Search for files.

```bash
find /home/kali -name "*.md"
```

### Practice exercise

Create a folder and file, then list it using `ls`.

### Recap

These commands help you navigate, create, inspect, and manage files.

### Review questions

1. What does `ls` do?
2. What is `mkdir` used for?
3. Why should `rm` be used carefully?

---

## 5. File permissions

Linux uses permissions to control whether a file can be read, written, or executed.

### Common symbols

- `r` = read
- `w` = write
- `x` = execute

### Command example

```bash
ls -l
```

This shows file permissions and ownership.

### Practice exercise

Run `ls -l` and look at the permission string.

### Recap

Permissions control who can access files and what they may do with them.

### Review questions

1. What does `ls -l` show?
2. What does `x` mean?
3. Why are permissions important?

---

## 6. Using `sudo`

`sudo` means “superuser do.” It lets you run commands with administrator privileges when allowed.

### Why do we need it?

Some system changes require higher privileges.

### Simple explanation

Use `sudo` only when you truly need it and understand the command.

### Example

```bash
sudo apt update
```

### Important warning

Do not run random commands with `sudo` without understanding them.

### Recap

`sudo` is powerful and should be used carefully.

### Review questions

1. What does `sudo` do?
2. Why is it dangerous to use carelessly?
3. What should you check before using it?

---

## 7. Installing tools with `apt`

Kali uses `apt` to update and install packages.

### Update package lists

```bash
sudo apt update
```

### Install a package

```bash
sudo apt install nmap -y
```

### Why do we need it?

It keeps your system up to date and allows you to install useful tools.

### Important rule

Only install software you need and understand.

### Practice exercise

Check whether a tool is already installed before installing it again.

### Recap

`apt` is the package manager used by Kali Linux.

### Review questions

1. What does `sudo apt update` do?
2. What is `apt install` used for?
3. Why should beginners avoid blind installs?

---

## 8. Verify whether a tool is installed

Use `which` or `command -v` to check if a command exists.

### Example

```bash
which msfconsole
```

or

```bash
command -v msfconsole
```

### Why do we need it?

It tells you whether the tool is available before you try to use it.

### Practice exercise

Run:

```bash
command -v msfconsole
```

### Recap

Checking tool availability prevents confusion and wasted commands.

### Review questions

1. What command checks whether a tool is installed?
2. Why is verification useful?
3. What is a common beginner mistake?

---

## 9. Reading command errors

Error messages contain clues. They usually tell you what went wrong and where.

### Example

```bash
ls /nonexistent-folder
```

This may return a "No such file or directory" error.

### Practice exercise

Run a harmless command that fails and read the error carefully.

### Common mistakes

- Ignoring the error.
- Guessing instead of reading the message.

### Recap

Error messages are useful and should be read carefully.

### Review questions

1. Why should you read errors?
2. What is a common beginner mistake?
3. What does the message often tell you?

## Next steps

Continue to [Installing Tools](./installing-tools.md).
