# HOW TO TEST THE SYSTEM

## Purpose

This document provides a simple method for independently testing the Bounded Power Framework (BPF) using real-world institutions.

The goal is to allow a reader to:

- understand how the system applies in practice  
- evaluate its strengths and weaknesses  
- identify gaps or failure points  

No prior expertise is required.

---

## Overview

Testing is done by selecting a real-world authority system and mapping it into the framework.

This can be done manually or with assistance from an AI system.

---

## Step 1 — Select a system

Choose a power-bearing authority.

Examples:

- a government agency  
- a police department  
- a regulatory body  
- a court system  
- a corporation or platform  
- a school district or university  
- a homeowners association  

The system should:

- exercise authority over people or resources  
- make decisions that affect others  

---

## Step 2 — Define the system

Describe the system in simple terms:

- What authority does it have?  
- What actions can it take?  
- Who does it affect?  
- What resources does it control?  

Do not aim for perfection. Approximate descriptions are sufficient.

---

## Step 3 — Generate a registration record

Use the provided form:

- `02-forms/registration.md`

You may:

- fill it out manually  
- or ask an AI to generate it  

Suggested prompt:

"""
Impersonate a neutral analyst. Using publicly available information and realistic assumptions, generate a completed version of this registration form for [SYSTEM NAME].

Do not use real names of individuals. Use general descriptions where necessary.
"""

The output should:

- reflect real-world behavior  
- include plausible constraints and authority definitions  
- remain anonymized at the individual level  

---

## Step 4 — Examine the result

Review the generated registration.

Ask:

- Is the authority clearly defined?  
- Are the limits explicit or vague?  
- Are there areas where power could expand?  
- Are dependencies visible?  

This step reveals how the system is currently structured.

---

## Step 5 — Apply framework constraints

Compare the system against BPF principles:

- Does authority expire?  
- Can actions be interrupted?  
- Are decisions reversible?  
- Are actions auditable?  

Identify gaps between:

- how the system operates  
- how the framework would constrain it  

---

## Step 6 — Identify failure modes

Look for:

- uncontrolled expansion paths  
- lack of interruption mechanisms  
- irreversible outcomes  
- hidden or untracked actions  

These are structural weaknesses.

---

## Step 7 — Attempt adaptation

Modify the system conceptually:

- add expiration conditions  
- introduce interruption triggers  
- require action logging  
- define explicit limits  

Evaluate:

- what changes would be required  
- whether they are feasible  
- what resistance would occur  

---

## Step 8 — Evaluate the framework

After testing, ask:

- Does the framework meaningfully constrain the system?  
- Where does it fail?  
- What assumptions break down?  
- What is missing?  

The purpose is not validation.

The purpose is stress-testing.

---

## Notes

- Precision is not required for testing  
- Approximation is sufficient  
- Different testers may produce different results  

This variability is expected and useful.

---

## Summary

To test the system:

1. Select a real authority  
2. Describe its structure  
3. Generate a registration record  
4. Compare it to framework constraints  
5. Identify gaps and failure modes  
6. Attempt structural corrections  

This process allows independent evaluation without requiring implementation.
