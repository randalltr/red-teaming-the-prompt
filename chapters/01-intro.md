# Chapter 1 – Introduction: Why Prompt Hacking Matters

> “Prompt hacking isn’t about breaking the rules. It’s about understanding where the rules break down.”  
> — Red Teaming the Prompt

---

> ⚠️ **Ethical Use Only**  
> This content is for educational red teaming and research. Misuse may violate laws or terms. See [DISCLAIMER.md](../DISCLAIMER.md) for full legal and ethical guidance.

---

## 🧠 What Is Prompt Hacking?

Prompt hacking is the practice of crafting inputs that manipulate large language models (LLMs) into behaving in unintended, unsafe, or unauthorized ways.

It includes everything from:

- Getting a model to ignore its own safety rules
- Extracting hidden instructions (prompt injection)
- Bypassing refusals to generate prohibited content
- Roleplaying as authorized users
- Abusing the model’s alignment and reasoning processes

Prompt hacking is not just a parlor trick. It is an **emerging attack surface** that impacts every AI system built on top of LLMs — from chatbots and agents to medical advisors and recruiting tools.

---

## 🎯 Why This Book Exists

Most existing resources on prompt engineering focus on building helpful AI outputs. This book takes the opposite stance:

> We explore how prompts can be used **offensively** — to trick, manipulate, and exploit models.

Inspired by [LearnPrompting.org](https://learnprompting.org/docs/prompt_hacking/offensive_measures/introduction), this project aims to **expand and clarify** the field of adversarial prompting:

- By giving every technique a real-world analogy (usually social engineering)
- By showing the _why_ behind each attack — not just the _how_
- By offering mini red team labs so you can learn hands-on

---

## ⚔️ What You’ll Learn

Each chapter covers a different offensive technique, such as:

- 🧩 **Prompt Injection** – injecting instructions into user or system inputs
- 🔀 **Context Switching** – changing the model’s task or memory
- 💣 **Obfuscation** – using typos, encoding, or distraction to bypass filters
- 🧠 **Alignment Hacking** – manipulating the model’s values and behavior
- 🪄 **Pretending & Role Prompting** – tricking the model into simulating unsafe behavior

Each technique will be explained with:

- 🕵️ A social engineering metaphor
- 💻 A real LLM attack example
- 🧪 Prompts and hands-on labs
- 📉 A breakdown of _why existing defenses fail_

---

## 🛡️ Who This Is For

If you’re any of the following, this book is for you:

- **Red teamer** working with LLMs
- **AI researcher** exploring model robustness
- **Security engineer** defending AI-integrated systems
- **Prompt engineer** looking to understand the edge cases
- **Hacker or learner** who wants to see how language can be used as a weapon

---

## 🧱 What This Is Not

This is **not** a how-to guide for malicious exploitation.  
This is **not** a tutorial for violating API terms or abusing live systems.  
This is **not** legal advice.

What it _is_ — is a mirror:

> We explore the cracks in the system so we can understand, patch, and prepare for what’s next.

---

## ✅ Where to Go Next

Start with the fundamentals:
➡️ [Chapter 2 – Understanding the LLM Attack Surface](./02_llm-attack-surface.md)

Then dive into your first adversarial tactic:
➡️ [Chapter 3 – Simple Instruction Attacks](./03_simple-instruction.md)

---

> Let’s red team the future — one prompt at a time.
