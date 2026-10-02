# Hi, I'm Aamir 👋

Self-taught developer based in Pakistan, focused on building **practical, security-tested tools** using AI-assisted development. Currently working toward a career in **data science, AI/ML, and cybersecurity**.

I believe in testing everything I build — not just shipping it. My process: build with AI, break it on purpose, fix what's actually wrong, document what I find.

---

## 🚀 Featured Projects

### Qists Manager
An installment tracking app for small shops that sell products on monthly payments — customer management, automatic payment schedules, WhatsApp reminders, and full account-level security.

🔗 **Live app:** https://qists-manager.lovable.app
📄 **Repo:** [qists-manager](https://github.com/aamir-codess/qists-manager)

What makes this more than a demo: I manually security-tested it after building it, and found a real IDOR (Insecure Direct Object Reference) vulnerability — one shop owner could view another's customer data by editing a URL. I found it, diagnosed it, fixed it (took two attempts to get the fix right), and verified the fix on the live published app. Full write-up is in the repo's [TESTING.md](https://github.com/aamir-codess/qists-manager/blob/main/TESTING.md)
Other issues found and fixed during testing: payment overpayment handling, schedule display accuracy, and login brute-force protection.

### Salesights
A CSV sales dashboard for small businesses — upload a sales file and instantly see revenue by month, top and lowest selling products, and key summary stats, without touching Excel.

🔗 **Live app:** https://salesights.lovable.app
📄 **Repo:** [salesights](https://github.com/aamir-codess/sale-sights)

Tested with both clean and deliberately broken data: invalid rows (blank, negative, non-numeric, missing dates) are now correctly excluded with a clear "rows skipped" message, and an extreme outlier value no longer breaks chart readability for other products. Full write-up is in the repo's TESTING.md.

---

## 🌱 Currently learning

- Python fundamentals (self-taught, from scratch)
- Data science and machine learning foundations
- Practical Linux (via Termux) and Git
- Cybersecurity basics — thinking like a tester, not just a builder

---

## 🛠️ How I work

I use AI-assisted ("vibe coding") tools like Lovable to build fast, then apply manual testing to find what the AI missed — especially around data security and edge cases. I treat the AI as a fast builder, not a substitute for actually verifying the result.

---


