# 8️⃣ Phase 8 · Layers of the Web: Surface, Deep, Dark

**⏱️ 42:30 – 50:50** · 📂 S01 Course Intro & Web Fundamentals · [⬅️ Prev](07-Phase7-Standards-In-The-Wild.md) · [Next ➡️](09-Phase9-Generations-of-Web.md)

---

## ⏱️ 42:30 – 43:36 · 🧩 Three Layers ⭐

🔑 **Key points**
- 🧅 The web (internet) is divided into **three layers**: **surface**, **deep**, **dark**.
- 🖼️ The instructor shows a web-layers diagram:
```
  ════════════════════════ 👀 what you see ════════════════════════
   🌊 SURFACE WEB   ~5%   email · Instagram · Facebook · Google
  ─────────────────────────────────────────────────────────────────
   🏢 DEEP WEB            govt & company internal websites
                          (only employees · only office network)
  ─────────────────────────────────────────────────────────────────
   ⚫ DARK WEB            military / armed-forces data
                          special browsers · misused for illegal activity
  ═════════════════════════════════════════════════════════════════
```

🧠 **Hook:** *Surface = you · Deep = employees · Dark = off-limits.*

---

## ⏱️ 43:36 – 44:14 · 🧩 🌊 Surface Web

🔑 **Key points**
- 📱 The web you use **every day**: emails, Instagram, Facebook, Google.
- 📊 It is **only ~5%** of the internet.
- 🔒 General users are allowed to access **only this 5%**, not deep or dark.

---

## ⏱️ 44:14 – 45:01 · 🧩 🏢 Deep Web: Organisations' Own Web

🔑 **Key points**
- 🏛️ **Government organisations** and **private companies** have their **own web**.
- 🧾 Examples named: e-Seva, the passport office, the Aadhaar office: offices with their own websites.

---

## ⏱️ 45:01 – 46:00 · 🧩 PFMS: A Deep-Web Example 🇮🇳

🔑 **Key points**
- 💰 **PFMS = Public Finance Management System**, Government of India, used by government offices **all over India**.
- 🗺️ **CFMS** = the same idea for **each state**.
- 🧾 **Problem it solves:** earlier, a govt office buying a printer/laptop called a **tender**; bills were inflated (*buy for ₹500, bill ₹50,000*).

---

## ⏱️ 46:00 – 47:02 · 🧩 "Amazon for Government Offices"

🔑 **Key points**
- 🛒 Offices **order what they need** on PFMS (e.g., 10 laptops for a Hyderabad office) and it is **delivered**.
- 🔍 Everything is **transparent**: how much was paid and spent.
- 🚫 Anyone can **open** the site, but you **cannot log in**. Even employees **can't log in from home**, only **from their office**.
- 🌐 It is designed to **detect your IP address**.

---

## ⏱️ 47:02 – 48:03 · 🧩 Wi-Fi Detection & What Deep Web Means

🔑 **Key points**
- 📶 It even **detects which Wi-Fi** you use. Office Wi-Fi only; another Wi-Fi → **disconnected**.
- 🏦 Same idea in daily life: **bank apps** warn *"You are connected to Wi-Fi. Are you sure?"*
- 🏢 **Almost all private organisations' and government professional websites** live in the **deep web**: accessible **only by their employees, only through their Wi-Fi**.
```
  👤 Employee at office  ── 📶 office Wi-Fi / office IP ──► ✅ PFMS login allowed
  👤 Employee at home    ── 📶 home Wi-Fi  / other IP   ──► ❌ disconnected
  👤 Public              ── 🌐 any network             ──► 👀 can open page, ❌ can't log in
```

---

## ⏱️ 48:03 – 49:00 · 🧩 ⚫ Dark Web

🔑 **Key points**
- 🎖️ Meant for **military / armed-forces operations**: their documents and information.
- ⚠️ But **used for a lot of illegal activities**.
- 🧭 Needs **special browsers** to access.
- 👮 Instructor: you are **continuously monitored**; it is **not legal** to go there; **don't ever attempt it**.

---

## ⏱️ 49:00 – 49:31 · 🧩 Where Pirated Movies Come From

🔑 **Key points**
- 🏴‍☠️ Pirated movies are uploaded and handled **through the dark web**.
- 🌍 Hard to control because those **servers are in other countries/locations**.

---

## ⏱️ 49:31 – 50:50 · 🧩 Same Tech for All Layers + Spotting the Stack 🔎

🔑 **Key points**
- 🧱 Surface, deep or dark: **all websites are built with HTML, CSS**: the concepts in this course.
- 🇮🇳 **Government of India** (as said): **React JS** for the **frontend** of government websites; **SAP** for **business transactions**.
- 🔎 Read the **URL** to guess the backend:
```
  https://…/page.aspx   ──►  🟦 .NET
  https://…/page.jsp    ──►  ☕ Java
  (PFMS: React frontend + .aspx → .NET)
```

🧠 **Hook:** *`.aspx` = .NET · `.jsp` = Java.*

---

## ✅ Quick Recall

```
  ☐ Name the 3 layers, and the share of the surface web
  ☐ Expand PFMS. What is CFMS?
  ☐ What problem did PFMS solve?
  ☐ 2 things PFMS checks before allowing login (IP · Wi-Fi)
  ☐ What is the dark web meant for, and how is it misused?
  ☐ Govt of India: frontend tech? business-transaction tech?
  ☐ .aspx → ?   .jsp → ?
```
