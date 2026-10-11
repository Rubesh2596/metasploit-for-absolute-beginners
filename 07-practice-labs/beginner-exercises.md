# Beginner Exercises

## Exercise 1: Confirm your terminal environment

**Objective:** Understand the difference between a normal shell and the Metasploit console.

**Prerequisites:** Kali Linux or a compatible terminal environment.

**Lab environment:** Local machine only.

**Commands:**

```bash
whoami
pwd
msfconsole --version
```

**Explanation:**

The first commands show basic shell information. `msfconsole --version` verifies whether the framework is installed.

**Expected observations:**

- You see your login name.
- You see the current directory.
- You see a version string or a command-not-found error.

**Cleanup steps:**

- Close the terminal when done.

**Review questions:**

1. What does `pwd` show?
2. What does `msfconsole --version` verify?
3. Why is the shell prompt different from the Metasploit prompt?

---

## Exercise 2: Search for modules safely

**Objective:** Learn how to search for modules without executing anything.

**Prerequisites:** `msfconsole` installed and available.

**Lab environment:** Local machine only.

**Commands:**

```text
msfconsole
search ssh
search http
search scanner
```

**Explanation:**

This exercise helps you identify module families without running anything on a target system.

**Expected observations:**

- You see search results with module names and descriptions.

**Cleanup steps:**

- Use `exit` to leave `msfconsole`.

**Review questions:**

1. What does `search` do?
2. Why is this a safe beginner exercise?
3. What should you read before selecting a module?

---

## Exercise 3: Inspect a module without running it

**Objective:** Learn how to read module details and required options.

**Prerequisites:** Access to `msfconsole`.

**Lab environment:** Local machine only.

**Commands:**

```text
msfconsole
search smb
info exploit/windows/smb/ms17_010_eternalblue
show options
```

**Explanation:**

This exercise teaches you to inspect a module and understand the values it requires. It is a read-only workflow.

**Expected observations:**

- The module description appears.
- Required and optional settings are listed.

**Cleanup steps:**

- Use `back` or `exit` when finished.

**Review questions:**

1. Why is `info` useful?
2. What does `show options` tell you?
3. What does selecting a module not automatically do?

---

## Exercise 4: Create a safe lab folder

**Objective:** Learn how to organize lab files safely on your system.

**Prerequisites:** Kali Linux terminal access.

**Lab environment:** Local machine only.

**Commands:**

```bash
mkdir -p ~/labs/metasploit-practice
cd ~/labs/metasploit-practice
pwd
ls -la
```

**Explanation:**

This helps keep notes and lab files organized in a safe local workspace.

**Expected observations:**

- You see the new folder and its contents.

**Cleanup steps:**

- Remove the folder only if you are sure you no longer need it.

**Review questions:**

1. Why is organization helpful in a lab?
2. What does `pwd` show?
3. Why should you avoid deleting files without understanding them?

---

## Exercise 5: Practice local networking basics

**Objective:** Inspect local network information without targeting external systems.

**Prerequisites:** Linux terminal access.

**Lab environment:** Local machine only.

**Commands:**

```bash
ip addr
ip route
ping -c 4 127.0.0.1
```

**Explanation:**

This exercise teaches you how to look at local interfaces, route information, and loopback connectivity.

**Expected observations:**

- You see interface addresses.
- You see route information.
- `ping` returns successful replies to localhost.

**Cleanup steps:**

- There is no destructive cleanup required.

**Review questions:**

1. What does `ip addr` show?
2. Why is `ping -c 4 127.0.0.1` a safe test?
3. What is the purpose of `ip route`?

## Final note

Beginner exercises should be simple, safe, and readable. Practice only on systems you own or are explicitly allowed to test.
