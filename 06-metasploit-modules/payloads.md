# Payloads

## 1. What is a payload?

A payload is the code that runs after a module or exploit successfully triggers a condition.

### Why do we need it?

The payload is the action that follows exploitation or module execution.

### Simple explanation

If the exploit creates the opening, the payload is what happens after the door opens.

### Example

A payload may start a shell or run commands on the target.

### Practice exercise

Look up examples of payloads in Metasploit and identify what they are intended to do.

### Common mistakes

- Choosing a payload without understanding the target environment.
- Assuming every payload works in every case.

### Recap

Payloads are the follow-up code that executes after a trigger.

### Review questions

1. What is a payload?
2. Why is payload selection important?
3. What is one possible payload action?

---

## 2. What is a shell?

A shell is a command environment that gives access to a system’s command prompt.

### Why do we need it?

It helps learners understand command execution after a successful lab exercise.

### Simple explanation

A shell is like a command line on the target machine.

### Practice exercise

Explain in your own words what a shell does.

### Recap

A shell provides a command environment on a target system.

### Review questions

1. What is a shell?
2. Why is it relevant to payloads?
3. What does a shell normally allow?

---

## 3. Reverse vs. bind connections

### Reverse connection
In a reverse connection, the target machine connects back to the attacker or lab machine.

### Bind connection
In a bind connection, the target waits for an incoming connection from the attacker side.

### Why do we need it?

The choice depends on network structure, firewalls, and the target environment.

### Simple explanation

Reverse connections often work better when the target is behind a firewall or NAT.

### Practice exercise

Explain the difference between a reverse and bind connection in one paragraph.

### Recap

Payload design depends on how the network and access model are arranged.

### Review questions

1. What is a reverse connection?
2. What is a bind connection?
3. Why might one be chosen over the other?

---

## 4. Staged vs. stageless payloads

### Staged payloads
A staged payload has more than one step and may download a second piece.

### Stageless payloads
A stageless payload is delivered as one complete package.

### Why do we need it?

Payload design can depend on environment, size, and target conditions.

### Simple explanation

A staged payload is like a two-step delivery; a stageless payload is delivered all at once.

### Practice exercise

Write one sentence explaining the difference between staged and stageless payloads.

### Recap

Payload architecture matters because it affects compatibility and delivery.

### Review questions

1. What is a staged payload?
2. What is a stageless payload?
3. Why does payload choice matter?

---

## 5. Risks and authorization

Payload execution can affect a target and should only happen in a safe, authorized environment.

### Why do we need it?

Every payload has consequences, so a learner must understand what it does and where it is allowed to run.

### Simple explanation

Even during learning, payloads are real tools with real effects.

### Practice exercise

List three reasons payload selection should be deliberate.

### Recap

Payloads are powerful tools that must be handled with care and permission.

### Review questions

1. Why should payloads be chosen carefully?
2. What does it mean to work in an authorized environment?
3. Why is this important for beginners?

## Next steps

Continue to [Sessions](./sessions.md).
