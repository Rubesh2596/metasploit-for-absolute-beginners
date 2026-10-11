# Lab Setup

## 1. Why a lab is necessary

A lab environment lets you practice safely without affecting real systems.

### Why do we need it?

Cybersecurity learning should happen in a controlled environment.

### Simple explanation

A lab is a safe place to test ideas, tools, and workflows without harming actual systems.

### Important terminology

- Virtual machine: a simulated computer running inside another machine.
- Host-only network: a private network only accessible to lab machines.
- Snapshot: a saved state of a VM you may restore later.

### Practice exercise

Write down the tools or machines you would use in your own safe lab setup.

### Common mistakes

- Testing on production systems.
- Forgetting to isolate the lab from real traffic.

### Recap

A lab is the right place to practice cybersecurity concepts safely.

### Review questions

1. Why is a lab necessary?
2. What is a virtual machine?
3. Why is isolation important?

---

## 2. Attacker machine vs. target machine

### Attacker machine
This is the machine you use to run tools and interact with the lab.

### Target machine
This is the machine being inspected or tested under controlled conditions.

### Example

Kali Linux may act as the attacker machine while a deliberately vulnerable VM acts as the target.

### Practice exercise

Describe the difference between the attacker machine and the target machine in one sentence each.

### Recap

The attacker machine runs tools; the target machine is the system being exercised.

### Review questions

1. What is the attacker machine?
2. What is the target machine?
3. Why is the distinction important?

---

## 3. Host-only networking

Host-only networking keeps lab machines on a private network that is not exposed to the internet.

### Why do we need it?

This prevents outside access and keeps the environment isolated.

### Simple explanation

Host-only networking is like putting your lab in a private room instead of on the public street.

### Practice exercise

Explain why a host-only network is safer than connecting a lab to the internet.

### Recap

Host-only networking keeps the lab private and contained.

### Review questions

1. What is a host-only network?
2. Why is it useful for learning?
3. What is the benefit of isolation?

---

## 4. Using snapshots

Snapshots save the state of a VM so you can restore it later.

### Why do we need it?

If something goes wrong, you can quickly restore a clean starting point.

### Simple explanation

A snapshot is like saving a checkpoint in a game.

### Practice exercise

Before making changes, take a snapshot of the VM and note its name.

### Common mistakes

- Forgetting to save a clean baseline.
- Not documenting which snapshot is the starting point.

### Recap

Snapshots make lab work easier to manage and recover from.

### Review questions

1. What is a snapshot?
2. Why is it helpful?
3. How does it improve safety?

---

## 5. Cleanup after exercises

Every lab should end with cleanup.

### Why do we need it?

This reduces confusion and helps leave the environment safe and organized.

### Simple explanation

Cleanup is like putting away your tools after a project.

### Practice exercise

After each lab, write down what you would shut down or reset.

### Recap

Cleanup keeps the lab safe and manageable.

### Review questions

1. Why is cleanup necessary?
2. What might you clean up after a lab?
3. Why is this better than leaving everything running?

---

## 6. Example safe lab setup

A simple safe workflow could include:

- Kali Linux as the attacker machine.
- A deliberately vulnerable VM as the target.
- Host-only networking.
- Snapshots before each exercise.
- No public internet exposure.

### Practice exercise

Design a small safe lab diagram in words.

### Recap

A safe lab is isolated, controlled, and easy to reset.

### Review questions

1. What kind of network should lab machines use?
2. Why should you avoid public connectivity?
3. Why is a snapshot useful?

## Next steps

Continue to [Beginner Exercises](./beginner-exercises.md).
