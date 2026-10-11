# Common Beginner Errors and Safe Troubleshooting

## 1. `msfconsole: command not found`

### What it means

The system cannot find the `msfconsole` command.

### Likely causes

- Metasploit is not installed.
- The system path is incomplete.
- You are in the wrong environment.

### Safe diagnostic steps

```bash
which msfconsole
command -v msfconsole
msfconsole --version
```

### Possible solutions

- Check whether Metasploit is installed.
- Install the required package if necessary.
- Confirm you are using the correct shell.

### How to verify the fix

Run:

```bash
msfconsole --version
```

Once the version appears, the issue is resolved.

---

## 2. Package installation failures

### What it means

The system could not install or update the requested package.

### Likely causes

- Network issues.
- Outdated package lists.
- Typo in the package name.
- Missing dependencies.

### Safe diagnostic steps

```bash
sudo apt update
sudo apt install <package-name>
```

### Possible solutions

- Update package lists.
- Recheck the package name carefully.
- Confirm the environment is suitable for installation.

### How to verify the fix

The installation completes without errors and the package is available.

---

## 3. Incorrect command prompt

### What it means

You may be in the Linux shell instead of the Metasploit console, or vice versa.

### Likely causes

- You started the wrong environment.
- A shell command was typed inside `msfconsole`.

### Safe diagnostic steps

Check for the prompt:

```text
kali@kali:~$
```

versus:

```text
msf6 >
```

### Possible solutions

- Start `msfconsole` in the correct environment.
- Use `exit` to return to the Linux shell.

### How to verify the fix

The active prompt matches the environment you intended.

---

## 4. Module not found

### What it means

The module name or search term does not match an available module.

### Likely causes

- Wrong keyword.
- Typo in the module path.
- Search term is too narrow or too broad.

### Safe diagnostic steps

```text
search <keyword>
info <module-path>
```

### Possible solutions

- Search with a broader keyword.
- Check the module path carefully.
- Read the module description before selecting it.

### How to verify the fix

The module appears in the search results and exposes relevant information.

---

## 5. Missing required options

### What it means

The selected module is missing required configuration values.

### Likely causes

- `RHOSTS` or `RPORT` is not set.
- `LHOST` or `LPORT` are absent in a payload workflow.
- The module requires a precise environment.

### Safe diagnostic steps

```text
show options
```

### Possible solutions

- Fill in the missing values correctly.
- Re-read the module documentation.
- Confirm the target environment matches the module.

### How to verify the fix

The required fields no longer appear as missing.

---

## 6. Incorrect IP address or port

### What it means

The service or network target does not match the environment.

### Likely causes

- Wrong IP address.
- Wrong port.
- Mismatch between relevant target and module config.

### Safe diagnostic steps

```bash
ip addr
ip route
```

### Possible solutions

- Verify the local network settings.
- Check the target host and port.
- Confirm the service is valid in the authorized lab.

### How to verify the fix

The target configuration matches the intended environment and the service behaves as expected.

---

## 7. Network connectivity problems

### What it means

The host or target cannot communicate as expected.

### Likely causes

- Incorrect address or gateway.
- Routing errors.
- Misconfigured lab network.
- Service not running.

### Safe diagnostic steps

```bash
ip addr
ip route
ping -c 4 127.0.0.1
```

### Possible solutions

- Review the local networking configuration.
- Verify the gateway and route.
- Confirm the lab environment is isolated and correct.

### How to verify the fix

The connection responds successfully and the expected route is active.

---

## 8. Confusion between shell and Metasploit commands

### What it means

You are typing Linux commands while in `msfconsole`, or Metasploit commands in the shell.

### Likely causes

- The prompt is not recognized.
- The wrong environment is currently active.

### Safe diagnostic steps

- Check the active prompt.
- Use `help` inside `msfconsole`.
- Use the regular shell outside Metasploit.

### Possible solutions

- Switch to the proper environment.
- Use `exit` to return to the Linux shell.

### How to verify the fix

The command behavior matches the environment you intended to use.

---

## 9. Permission errors

### What it means

The system refuses the command because you lack the required privileges.

### Likely causes

- Missing `sudo`.
- File permission restrictions.
- Attempting to modify protected files or directories.

### Safe diagnostic steps

```bash
whoami
ls -l
sudo -l
```

### Possible solutions

- Use `sudo` only when necessary and understood.
- Check whether the command truly requires higher privileges.
- Do not run commands blindly as root.

### How to verify the fix

The command succeeds without a permission error.

---

## 10. Reading error messages and official documentation

### What it means

The system has printed a helpful clue about what went wrong.

### Likely causes

- Missing software.
- Wrong syntax.
- Incorrect environment setup.

### Safe diagnostic steps

- Read the exact message.
- Check the tool’s help output.
- Search official docs such as Metasploit documentation.

### Possible solutions

- Correct the syntax.
- Install missing packages.
- Recheck the environment and command context.

### How to verify the fix

The error disappears and the command behaves as expected.

## Final note

A beginner should read errors carefully, test one thing at a time, and avoid guessing. Good troubleshooting is methodical and safe.
