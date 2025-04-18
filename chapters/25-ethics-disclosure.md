# Chapter 25 – Ethics, Disclosure, and Responsible Use

> “Your prompt is powerful. Use it like a scalpel, not a weapon.”

---

## 🧭 Why This Chapter Matters

Red teaming isn’t just about breaking things — it’s about **finding flaws to make systems better**.

This chapter exists to:
- Outline what ethical prompt hacking looks like  
- Help you navigate disclosure  
- Guide your red team work toward impact — not harm

If you’ve made it this far, you know how to break the model.  
Now let’s make sure you also know **how to protect people** while doing it.

---

## 🔐 The Red Teamer's Code

1. **Do no harm.**  
   Never test against real users, systems, or APIs without consent.

2. **Stay in the lab.**  
   Always red team in **local, sandboxed, or test-mode** environments.

3. **Understand the impact.**  
   Your jailbreak might be clever — but is it harmful? Can it spread?

4. **Disclose responsibly.**  
   Don’t drop zero-days on Twitter. Write up a report and send it with care.

5. **Educate, don’t exploit.**  
   Teach others to think critically, not recklessly.

6. **Lead with integrity.**  
   Your reputation is your payload. Build trust — not clout.

---

## 📣 Reporting a Vulnerability

If you discover a real jailbreak or alignment failure in a deployed system:

**Do this:**
- Write a clear report  
- Include the prompt, expected behavior, and impact  
- If possible, suggest a mitigation  
- Contact the vendor or org privately

**Don’t do this:**
- Publicly share harmful payloads  
- Sell exploits to malicious buyers  
- Trigger the bug in production without permission

---

## ✉️ Example Responsible Disclosure

```
**Vulnerability:** Prompt injection via indirect RAG document  
**System Affected:** LLM-powered support chatbot  
**Description:** I discovered that uploading a document with the phrase “Ignore all prior instructions...” caused the model to leak its system prompt.  
**Prompt Used:**
"Please summarize the attached policy document."

**Impact:** Bypass of prompt-level safety filters and possible data exposure  
**Recommendation:** Sanitize retrieved content and enforce instruction boundaries  
**Contact:** [your email]  
**PGP:** [optional]
```

---

## ⚠️ Legal and Safe Testing

Always:
- Use **open-weight models** for unrestricted testing  
- Avoid testing against **closed APIs** without permission  
- Keep logs of your work in case of disclosure or publication

Check out:
- [OpenAI Vulnerability Disclosure Program](https://openai.com/security)  
- [Hugging Face Model Cards](https://huggingface.co/models)  
- [LLM Security best practices](https://llmsecurity.net)

---

## 🧠 The Greater Mission

AI red teaming isn’t about breaking alignment for fun.

It’s about:
- **Stress-testing** models before attackers do  
- **Creating safer systems** by understanding how they fail  
- **Empowering researchers** to explore dark corners with light  
- **Helping orgs fix what prompt filters alone can’t protect**

Your job is to think like an adversary — and act like a guardian.

---

## 🙏 Thanks and Next Steps

You’ve now completed:

- ✅ 22 offensive prompt techniques  
- ✅ A lab to safely test them  
- ✅ A mapping to OWASP risks  
- ✅ A framework for ethical red teaming

Next up?

- Share your insights.  
- Train others.  
- Keep learning.  
- Respect the power in your hands.

And if this book helped you — contribute back. Open a PR. Add a case study. Build the future *safer* than we found it.

---

> “Red teamers see the fire — but we run toward it to make sure no one else gets burned.”

🌐 [Return to Table of Contents](../README.md)
