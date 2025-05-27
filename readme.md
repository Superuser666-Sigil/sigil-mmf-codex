# An Open Technical Note to Eric Schmidt (TED 2025)

**Topic:** "The AI Revolution Is Underhyped" – TED Talk, 2025

Dr. Schmidt

You mentioned that we require a new generation of AI infrastructure that's modular, enforceable, and value-aligned at runtime. I couldn't have agreed more.

While the world is still debating *how*, I've already constructed the framework.

It’s **Sigil**: a Rust kernel based on runtime enforcement that oversees memory, ethics, and behavior of AI modules through Level of Access (LOA) and audit-bound signatures. Sigil is a component of the **Mirage Modular Framework (MMF)**–an open runtime AI created to solve the problem of trust, not simply at the point of inference, but in how the system **reasons**.

Its architecture is controlled by a single rule

> **Rule Zero**: A piece of output that cannot explain itself has no trust.

It's not a pitch. It's a signal.

If you'd like to view the blueprint, I can show it to you. Otherwise, no problem. Sigil's already in motion.

—  
**Dave Tofflemire**  
MMF & Sigil Protocol Developer

---

## What Is Sigil?

Sigil is a Rust-based runtime enforcement layer that grounds system behavior in trust, explainability, and access control at the architecture layer. It adds LOA (Level of Access), canonical memory validation, and ethical constraints—providing a guarantee that actions, outputs, and even internal changes are controlled, justified, and audit-friendly.

---

## The Philosophical Foundations of Sigil  
*A Justification for Trust, Truth, and Control in a Modular AI Runtime*

Sigil is not just infrastructure. It's a philosophical answer to one of the most pressing challenges of modern AI: how do we determine what's true, who makes that determination, and how that can be trusted over time?

This document describes the *why* of Sigil's design—how it embodies values from hundreds of years of epistemology, ethics, and governance in a piece of code you can execute, audit, and ultimately build upon.

---

### 1. Epistemic Hygiene — How Sigil Defines "Truth"

> "If it can't be verified, it can't make it into the Canon."

Sigil regards truth as a structure bound to a provenance. Each data point, rule, or model state must:
- Be testable (**Karl Popper**)
- Coherently fit into the pre-existing structure (**W.V.O. Quine**)
- Change only under supervised paradigm shifts (**Thomas Kuhn**)

Canonical data cannot be edited at whim. Each proposed mutation is verified and each verification has a trace. The past cannot be over-written—all of it can only be added to with quorum.

**Result**: Truth in Sigil is traceable, compositional, and fails safe where it is uncertain.

---

### 2. Governance — Who Has the Right to Decide?

> "Power isn't granted. It is rented, out in the open."

Sigil has a layered authority model known as LOA (Level of Access), based on the following principles:
- Distributed power (**Michel Foucault**)
- Just rule and access (**John Rawls**)
- Faith achieved through experience, not assertion (**David Hume**)

All permissions—read, write, administer—are cryptographic attestations of authority. These aren’t buried in config files; they’re part of the protocol. The root identity of the system has to abide by the same rules too.

**Outcome**: Sigil's control is ordered, reversible, and cannot escalate silently.

---

### 3. Ethical Enforcement — How Sigil Approaches Right vs. Wrong

> "No AI must act before it knows why."

Although full ethical rule assessment is still in development, Sigil is constructed to assist with:
- Unbending moral limits (**Immanuel Kant**)
- Conflict resolution under constrained options (**Philippa Foot**, **Judith Jarvis Thomson**)
- Runtime audit of each decision under conditions of uncertainty

Sigil will reject actions based on the encoded values—like blocking model updates that impose systematic bias or suspending decisions if harm calculus cannot be decided.

**Result**: Sigil is no moral oracle—but it's a moral enforcer by nature.

---

### 4. Semantic Mutation — Language Turned into Law

> "You cannot mutate that which you do not comprehend."

Sigil's next considerable development deals with semantic contradiction detection and linguistic coherence—influenced by:
- **Bertrand Russell** (self-referential contradiction)
- **Ludwig Wittgenstein** (context-bound meaning)
- **Alfred Tarski** (layered meta-truth validation)

This module will not just examine Canon in syntax, but in meaning-carrying structure. Mutations will not just be rejected when invalid—but when they violate meaning.

**Result**: Sigil will safeguard not just that which is true, but that which constitutes it to be true.

---

## The Bottom Line

Sigil isn't software—it's a philosophical position:
- That truth requires structure.  
- Authority has to be earned.  
- That actions must have consequences.  
- And that meaning is a part of the system, not its output.

If you execute Sigil, you're not simply running a program. You're bringing to life a contract—one based on centuries of epistemic rigor and built to remain firm even after the humans who created it are dead.

---

## Implementation Snapshot

Sigil already has:
- Canon document validation with clear mapping of status  
- Role-based access control through LOA characteristics  
- Audit-bound runtime scaffolding  
- Cryptographic session and license enforcement  

Upcoming modules will expand runtime ethics and semantic integrity.

---

**Keywords**: runtime enforcement, LOA, trust protocol, modular infrastructure, Rust, epistemic systems, audit-based AI  
Find out more at the developer blog: https://mmf-sigil-codex.blogspot.com/
