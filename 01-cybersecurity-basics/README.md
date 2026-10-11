# Module 01: Cybersecurity Basics

## 1. What is cybersecurity?

Cybersecurity is the practice of protecting computer systems, networks, data, and people from harm. It includes keeping information private, making sure systems work correctly, and preventing attacks.

### Why do we need it?

Modern life depends on computers and the internet. Without security, data can be stolen, systems can break, and people can lose money or privacy.

### Simple explanation

Think of cybersecurity like protecting a house. Locks, cameras, alarms, and rules all help keep a place safe.

### Important terminology

- Threat: something that could cause harm.
- Risk: the chance a problem might happen.
- Asset: a valuable thing such as a computer, file, or network.

### Example

A company protects its customer database with passwords, access controls, and monitoring tools.

### Practice exercise

Write down three digital assets in your home, school, or lab environment.

### Common mistakes

- Thinking cybersecurity is only “hacking.”
- Ignoring prevention and monitoring.
- Assuming a system is safe without checks and updates.

### Recap

Cybersecurity is about protecting systems, users, and information from harm.

### Review questions

1. What is cybersecurity in simple English?
2. Why is protection important?
3. What is an asset?

---

## 2. What is ethical hacking?

Ethical hacking means using hacking skills in a legal, authorized, and responsible way to test and improve security.

### Why do we need it?

Security teams want to find weak points before attackers do.

### Simple explanation

An ethical hacker acts like a careful tester. They identify weaknesses and report them so they can be fixed.

### Real-world analogy

A building owner may hire a trusted inspector to check a property before openings or renovations.

### Important terminology

- Authorization: permission to test a system.
- Scope: the exact systems or rules for testing.
- Report: documentation of the findings.

### Example

A company may approve a test against a training lab environment and then review the results.

### Practice exercise

List two differences between an authorized security test and an unauthorized attack.

### Common mistakes

- Assuming all hacking is bad.
- Testing without permission.
- Forgetting to document findings.

### Recap

Ethical hacking is a responsible way to find vulnerabilities before they can be misused.

### Review questions

1. What does ethical hacking mean?
2. Why is authorization important?
3. What is scope?

---

## 3. What is penetration testing?

Penetration testing, or pen testing, is a controlled way to evaluate the security of a system or network.

### Why do we need it?

It helps teams discover weaknesses in a structured, authorized way.

### Simple explanation

A penetration tester simulates an attack, but only in an environment where this is allowed.

### Important terminology

- Target: the system being tested.
- Test environment: a safe place where testing is allowed.
- Findings: discovered weaknesses.

### Example

A lab environment might contain a vulnerable VM that is legal to evaluate under a defined scope.

### Practice exercise

Explain why a controlled environment matters.

### Common mistakes

- Forgetting the importance of scope.
- Testing public or production systems without permission.

### Recap

Penetration testing is structured testing within a clear scope and authorization.

### Review questions

1. What is penetration testing?
2. Why do organizations use it?
3. What is a target?

---

## 4. What is a vulnerability assessment?

A vulnerability assessment is the process of identifying weaknesses in systems, software, or configuration.

### Why do we need it?

It shows what needs attention before a real attacker can exploit it.

### Simple explanation

This is like an inspection: you look for weak spots, missing patches, and bad settings.

### Example

A vulnerability assessment may find an outdated service or a misconfigured firewall.

### Practice exercise

Name one type of weakness that a security assessment might identify.

### Common mistakes

- Confusing assessment with exploitation.
- Thinking one check is enough.

### Recap

A vulnerability assessment helps identify weaknesses before they are exploited.

### Review questions

1. What is a vulnerability assessment?
2. Why is it useful?
3. What is a patch?

---

## 5. What is a vulnerability?

A vulnerability is a weakness in software, hardware, or configuration that may be exploitable under the right conditions.

### Why do we need it?

Weaknesses can cause real impact if they are exposed and misused.

### Simple explanation

A vulnerability is like a weak lock on a door or a crack in a wall.

### Important terminology

- Exploit: the method or code used to take advantage of the flaw.
- Risk: the possible impact of a weakness being misused.

### Example

A web application may have a flaw that allows a malformed request to be processed incorrectly.

### Practice exercise

Explain the difference between a vulnerability and an exploit in one sentence each.

### Common mistakes

- Mixing up the flaw with the attack used against it.
- Assuming every weakness is immediately dangerous.

### Recap

A vulnerability is a weakness that may be exploitable.

### Review questions

1. What is a vulnerability?
2. How is it different from an exploit?
3. Why should it be fixed?

---

## 6. What is an exploit?

An exploit is a method, tool, or script that takes advantage of a vulnerability.

### Why do we need it?

An exploit allows a tester to trigger or demonstrate the flaw under controlled conditions.

### Simple explanation

If the vulnerability is the weak point, the exploit is the thing used to test that weak point.

### Example

A module in Metasploit may be designed to target a specific vulnerability in a service.

### Practice exercise

Explain the difference between a vulnerability and an exploit in plain English.

### Common mistakes

- Thinking every exploit works everywhere.
- Ignoring compatibility and target conditions.

### Recap

An exploit is the technique used to take advantage of a weakness.

### Review questions

1. What is an exploit?
2. Why is compatibility important?
3. How is it different from the vulnerability itself?

---

## 7. What is a payload?

A payload is the code that executes after a vulnerability is triggered or an exploit runs.

### Why do we need it?

The payload is the action that follows the successful trigger.

### Simple explanation

If exploitation creates the opening, the payload is what happens afterward.

### Important terminology

- Shell: a command environment with access to a system.
- Reverse connection: the target connects back to the attacker or lab machine.
- Bind connection: the target waits for an incoming connection.

### Example

A payload may create a shell or run a command on the target after a successful exercise.

### Practice exercise

List two possible actions a payload might take.

### Common mistakes

- Choosing a payload without checking the target environment.
- assuming payloads are automatic or harmless.

### Recap

A payload is the code that runs after a successful trigger or module interaction.

### Review questions

1. What is a payload?
2. Why is payload choice important?
3. What is a shell?

---

## 8. What is an attack surface?

An attack surface is all the ways a system could be reached or interacted with.

### Why do we need it?

A larger attack surface means more places to protect and review.

### Simple explanation

Think of it as all the doors, windows, and gaps in a building that someone could try to use.

### Example

A server may expose ports, applications, and services that create multiple entry points.

### Practice exercise

List one service or application that could add to an attack surface.

### Recap

The attack surface is the set of possible entry points into a system.

### Review questions

1. What is an attack surface?
2. Why does it matter?
3. What is one example of an entry point?

---

## 9. What is a security lab?

A security lab is a controlled environment used to practice cybersecurity skills without affecting real systems.

### Why do we need it?

It keeps learning safe and legal while allowing you to practice tools and workflows.

### Simple explanation

A lab is a sandbox where you can build skills without risking production systems.

### Important terminology

- Virtual machine: a simulated computer running inside another machine.
- Host-only network: a private lab network that is not connected to the internet.
- Snapshot: a saved state of a VM you can restore later.

### Example

A learner may run Kali Linux and a deliberately vulnerable VM on a private network.

### Practice exercise

Explain why a lab is safer than testing on a real network.

### Common mistakes

- Putting vulnerable machines on a public network.
- Forgetting to isolate the lab from real devices.

### Recap

A security lab provides a safe place to practice and learn.

### Review questions

1. What is a security lab?
2. Why is isolation important?
3. What is a snapshot?

---

## 10. Attacker, target, and security tester

These roles are different and important to understand.

### Attacker
An attacker tries to exploit a vulnerability or cause harm.

### Target
The target is the system or service being tested.

### Security tester
A security tester works with permission, follows scope, and documents findings.

### Example

In a lab, a security tester may use an intentionally vulnerable virtual machine under controlled conditions.

### Practice exercise

Write one sentence describing the difference between an attacker and a security tester.

### Recap

The roles differ because the goals and permissions differ.

### Review questions

1. What is a target?
2. How is a security tester different from an attacker?
3. Why is authorization important?

---

## 11. Why authorization matters

Authorization is permission to perform a security test or activity.

### Why do we need it?

Without it, you may break laws, policies, or trust boundaries.

### Simple explanation

If you want to inspect a house, you need the owner’s permission. The same is true for a system or network.

### Example

Testing a lab machine you own is different from scanning a public server or university network without permission.

### Practice exercise

Name two situations where you should not perform testing.

### Common mistakes

- Thinking the word “lab” excuses all testing.
- Ignoring permission and scope.

### Recap

Authorization makes security work legal, ethical, and safe.

### Review questions

1. What is authorization?
2. Why is it necessary?
3. What happens if you test without permission?

---

## 12. Learning security vs. attacking systems without permission

This repository is about learning and safe practice. It is not about attacking systems or harming others.

### Why do we need to say this?

People studying cybersecurity must separate education from misuse.

### Simple explanation

You may study a vulnerability in a lab, but you should not test a real system without permission.

### Example

Scanning a public system is not appropriate; testing a deliberately vulnerable lab VM is.

### Practice exercise

Write one difference between a safe lab exercise and an unauthorized real-world attack.

### Recap

Learning should be responsible, ethical, and permission-based.

### Review questions

1. Why is it important to separate learning from misuse?
2. What is the safest environment for beginner exercises?
3. Why should beginners avoid public systems?

---

## Beginner exercise

### Exercise: identify key terms

**Objective:** Learn and explain the major cybersecurity terms.

**Prerequisites:** None.

**Commands:** None. This is a writing exercise.

**Task:** Write a short definition for the following terms:

- Cybersecurity
- Vulnerability
- Exploit
- Payload
- Authorization
- Security lab

**Expected observation:** You should be able to explain each concept in plain English.

**Review questions:**

1. Which term means a weakness?
2. Which term means the method used against that weakness?
3. Why is authorization important?

## Next steps

Continue to [Module 02: Networking Fundamentals](../02-networking-fundamentals/ip-addresses.md).
