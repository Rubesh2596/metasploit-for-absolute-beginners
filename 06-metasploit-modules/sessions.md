# Sessions

## 1. What is a session?

A session in Metasploit represents an active communication channel or managed interaction with a target.

### Why do we need it?

Sessions help the framework keep track of active interactions in a structured way.

### Simple explanation

A session is like an open connection or active control channel that the tool can manage.

### Practice exercise

Review the session-related help in `msfconsole` and note what a session means in context.

### Common mistakes

- Thinking a session appears without setup.
- Forgetting that sessions depend on a valid environment and authorization.

### Recap

A session is a managed interaction created in the framework.

### Review questions

1. What is a session?
2. Why is it important in Metasploit?
3. What does it represent?

---

## 2. How sessions differ from normal terminal processes

A Metasploit session is not just a regular shell command; it is a tracked interaction within the framework.

### Why do we need it?

It helps learners understand the difference between using a Linux shell and using a structured security framework.

### Simple explanation

A normal terminal command is just a local shell action. A Metasploit session is a managed communication path created in the framework.

### Practice exercise

Read the help text related to Metasploit sessions and describe the difference in your own words.

### Recap

Sessions are active, managed interactions, not just regular terminal commands.

### Review questions

1. How is a Metasploit session different from a normal shell command?
2. Why is session tracking useful?
3. What does this teach you about the framework?

---

## 3. Safe termination of sessions

When a lab session is finished, it should be terminated properly.

### Why do we need it?

This keeps the environment organized and reduces confusion.

### Example concept

Metasploit includes session-management commands for interacting with or closing active sessions.

### Practice exercise

Review the help output for session-related commands and explain why cleanup is important.

### Common mistakes

- Leaving lab sessions open.
- Forgetting to clean up the environment after a practice exercise.

### Recap

Proper cleanup is part of safe learning.

### Review questions

1. Why should sessions be terminated safely?
2. What is the value of cleanup after a lab?
3. Why should learners avoid leaving sessions open?

## Next steps

Continue to [Lab Setup](../07-practice-labs/lab-setup.md).
