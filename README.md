# Metasploit for Absolute Beginners 🚀

A beginner-friendly, ethical learning guide for understanding cybersecurity fundamentals and the Metasploit Framework on Kali Linux.

## Introduction

This repository is designed for complete beginners who want to learn how Metasploit works, why it matters in cybersecurity, and how to practice safely in a lab environment. The goal is not to encourage misuse. It is to help you build strong foundations in networking, Linux, and ethical testing practices before you try any Metasploit workflows.

This project documents a learning journey in simple, practical language. You will find beginner explanations, command examples, and safe practice exercises.

## Who this repository is for

- Complete beginners in cybersecurity.
- Students learning networking and Linux basics.
- People preparing for ethical hacking or penetration testing labs.
- Learners using Kali Linux and trying to understand the Metasploit Framework.
- Anyone who wants a structured, beginner-friendly roadmap.

## Learning objectives

By the end of this repository, you should be able to:

- Explain the basics of cybersecurity and ethical testing.
- Understand networking concepts like IP addresses, ports, and protocols.
- Use common Kali Linux terminal commands safely.
- Explain what Metasploit is and how it fits into an authorized workflow.
- Understand the purpose of `msfconsole` and common commands.
- Recognize Metasploit module types such as exploits, auxiliary modules, payloads, and sessions.
- Set up an isolated cybersecurity lab and practice responsibly.
- Troubleshoot beginner errors without guessing.

## Prerequisites

Before using this repository, it helps to have:

- A computer running Kali Linux or a compatible Linux environment.
- Basic familiarity with opening a terminal.
- Access to a safe, isolated lab environment.
- Permission to practice in any lab environment you use.

## Recommended learning order

1. [01 - Cybersecurity Basics](./01-cybersecurity-basics/README.md)
2. [02 - Networking Fundamentals](./02-networking-fundamentals/ip-addresses.md)
3. [03 - Kali Linux Basics](./03-kali-linux-basics/terminal-commands.md)
4. [04 - Metasploit Introduction](./04-metasploit-introduction/what-is-metasploit.md)
5. [05 - Learning msfconsole](./05-learning-msfconsole/basic-commands.md)
6. [06 - Metasploit Modules](./06-metasploit-modules/exploits.md)
7. [07 - Practice Labs](./07-practice-labs/lab-setup.md)
8. [08 - Notes and Troubleshooting](./08-notes-and-troubleshooting/common-errors.md)
9. [Glossary](./GLOSSARY.md)

## Table of contents

### Module 01: Cybersecurity Basics
- [Module 01 Overview](./01-cybersecurity-basics/README.md)

### Module 02: Networking Fundamentals
- [IP Addresses](./02-networking-fundamentals/ip-addresses.md)
- [Ports and Protocols](./02-networking-fundamentals/ports-and-protocols.md)
- [TCP vs. UDP](./02-networking-fundamentals/tcp-vs-udp.md)

### Module 03: Kali Linux Basics
- [Terminal Commands](./03-kali-linux-basics/terminal-commands.md)
- [Installing Tools](./03-kali-linux-basics/installing-tools.md)

### Module 04: Metasploit Introduction
- [What Is Metasploit?](./04-metasploit-introduction/what-is-metasploit.md)
- [Installation](./04-metasploit-introduction/installation.md)
- [Starting msfconsole](./04-metasploit-introduction/starting-msfconsole.md)

### Module 05: Learning msfconsole
- [Basic Commands](./05-learning-msfconsole/basic-commands.md)
- [Searching Modules](./05-learning-msfconsole/searching-modules.md)
- [Understanding Options](./05-learning-msfconsole/understanding-options.md)

### Module 06: Metasploit Modules
- [Exploit Modules](./06-metasploit-modules/exploits.md)
- [Auxiliary Modules](./06-metasploit-modules/auxiliary.md)
- [Payloads](./06-metasploit-modules/payloads.md)
- [Sessions](./06-metasploit-modules/sessions.md)

### Module 07: Practice Labs
- [Lab Setup](./07-practice-labs/lab-setup.md)
- [Beginner Exercises](./07-practice-labs/beginner-exercises.md)

### Module 08: Notes and Troubleshooting
- [Common Errors](./08-notes-and-troubleshooting/common-errors.md)

### Supporting files
- [Glossary](./GLOSSARY.md)

## Learning progress checklist

- [ ] I understand what cybersecurity is.
- [ ] I understand the difference between learning and unauthorized attacks.
- [ ] I know the basics of IP addresses, ports, and protocols.
- [ ] I can use common Linux terminal commands safely.
- [ ] I know how to verify whether Kali tools are installed.
- [ ] I understand what Metasploit is and how it fits into a lab workflow.
- [ ] I understand key `msfconsole` commands such as `help`, `search`, `info`, and `use`.
- [ ] I can tell the difference between exploits, auxiliaries, payloads, and sessions.
- [ ] I know how to set up a safe lab environment.
- [ ] I can recognize beginner errors and look up official guidance.

## Troubleshooting

If something goes wrong, do not guess. Use a step-by-step approach:

1. Re-read the command and confirm the prompt.
2. Check whether the tool is installed.
3. Confirm whether you are in the correct terminal or `msfconsole` session.
4. Verify your IP and port settings in a lab environment.
5. Search official documentation when unsure.
6. Stop and ask for help if a command could affect a real system.

## Ethics and authorization

This repository is for legal, ethical, and educational cybersecurity learning only.

You must:

- Only practice on systems you own or have explicit permission to test.
- Use isolated virtual machines or lab environments.
- Respect local and organizational security policies.
- Avoid targeting public IPs, production systems, or third parties.

Understanding a concept is not the same as using it against a real target. The purpose of this project is to teach fundamentals, safe workflows, and responsible lab practice.

## Official references

- Metasploit documentation: https://docs.metasploit.com/
- Rapid7 Metasploitable 2 documentation: https://docs.rapid7.com/metasploit/metasploitable-2/
- Kali Linux documentation: https://www.kali.org/docs/

## How beginners can contribute

This repository is meant to grow as a learning project. Beginners can contribute by:

- Clarifying difficult concepts.
- Adding examples and explanations.
- Improving formatting and navigation.
- Suggesting useful lab exercises.
- Adding links to beginner-friendly references.

## Project status

This repository is a learning project and its documentation can evolve over time. New lessons, corrections, and improvements are welcome.

## Previewing the documentation in VS Code

To preview the Markdown files in VS Code:

1. Open a lesson file in the editor.
2. Press `Ctrl+Shift+V` to open the preview side-by-side.
3. Or use the Markdown preview button in the editor toolbar.

## Git commands for review and commit

```bash
git status
git diff
git add .
git commit -m "Add beginner-friendly Metasploit learning content"
```

## Final note

This guide is intentionally beginner-friendly. It introduces the essentials gradually, so you can understand each concept before moving to more advanced topics. Learn in small steps, practice in a safe environment, and keep improving.
