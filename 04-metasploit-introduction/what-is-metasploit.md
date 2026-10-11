# What Is Metasploit?

## 1. What is the Metasploit Framework?

Metasploit Framework is a collection of tools and modules used in cybersecurity learning and authorized testing.

### Why do we need it?

It gives a structured method to study vulnerabilities, payloads, and exploitation concepts in a controlled environment.

### Simple explanation

Metasploit is a framework that organizes tools and modules, rather than a single magic command.

### Important terminology

- Framework: a structured environment for tools.
- Module: a reusable unit of functionality.
- `msfconsole`: the main command-line interface in Metasploit.

### Example

A learner might search for a module and read its documentation before using it.

### Practice exercise

Open a terminal and run:

```bash
msfconsole --version
```

### Common mistakes

- Assuming it can magically attack anything.
- Forgetting that a module needs proper setup and authorization.

### Recap

Metasploit is a structured framework for authorized learning and testing.

### Review questions

1. What is Metasploit?
2. Why is it useful in cybersecurity education?
3. What is `msfconsole`?

---

## 2. What is it used for?

Metasploit is used to:

- Study module behavior.
- Read descriptions and options.
- Understand exploits and payloads.
- Build safe lab workflows.

### Why do we need it?

It helps learners understand how a security tool organizes modules and tasks.

### Practice exercise

Write a short sentence about one reason a learner might use Metasploit in a lab.

### Recap

Metasploit is a framework for learning and safe documentation-based testing, not for random attack attempts.

### Review questions

1. What does Metasploit help you do?
2. Why is it not a magic attack tool?
3. What is a module?

---

## 3. What it cannot automatically do

Metasploit cannot decide your target, environment, or permission for you.

### Why do we need it?

Real security work requires correct configuration, authorization, and understanding.

### Simple explanation

A module can explain what it needs, but it cannot guess your lab setup or legal permission.

### Example

A module may require `RHOSTS`, `RPORT`, and a compatible payload.

### Practice exercise

Explain why a module needs options before it can do anything meaningful.

### Recap

Metasploit is not an automatic decision-maker; it is a tool that must be configured and used responsibly.

### Review questions

1. What is one thing Metasploit cannot guess for you?
2. Why are required options important?
3. Why is authorization still necessary?

---

## 4. Metasploit in an authorized workflow

Metasploit fits into a safe workflow when used on your own systems or a lab environment with explicit permission.

### Example workflow

1. Set up an isolated lab.
2. Verify the system and network settings.
3. Read module documentation.
4. Inspect options and prerequisites.
5. Perform only authorized exercises.

### Practice exercise

Write a simple safe workflow for a beginner using Metasploit in a lab.

### Recap

Metasploit belongs in a planned and authorized workflow.

### Review questions

1. What makes a workflow safe?
2. Why is authorization essential?
3. What should you do before using a module?

---

## 5. Metasploit Framework vs. Metasploit Pro

### Metasploit Framework
A flexible, open-source toolset often used for learning and console-based testing.

### Metasploit Pro
A commercial product with additional enterprise features.

### Why do we need it?

Students usually start with the Framework because it is accessible and teaches the foundations clearly.

### Practice exercise

Explain the difference between the Framework and the commercial product in one sentence.

### Recap

Framework is the learning-focused route; Pro is a commercial product with more enterprise features.

### Review questions

1. What is the Metasploit Framework?
2. Why would a learner choose it?
3. What is a key difference from Metasploit Pro?

## Next steps

Continue to [Installation](./installation.md).
