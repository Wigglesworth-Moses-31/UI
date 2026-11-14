# 4️⃣ Phase 4 · NPM & Package Managers

**⏱️ 19:38 – 24:35** · 📂 S02 Dev Environment Setup · [⬅️ Prev](03-Phase3-Install-Verify-Nodejs.md) · [Next ➡️](05-Phase5-NPM-In-Action-Bootstrap.md)

---

## ⏱️ 19:38 – 20:01 · 🧩 NPM = Node Package Manager ⭐🎯

🔑 **Key points**
- 📦 **NPM** stands for **Node Package Manager**. *"Very important."*
- 🎬 **Seen on screen:** the terminal now shows both checks (`>npm -v` → `11.12.1`, 19:39), then this line is typed in the notes file (bold as shown):
```text
- NPM is Node Package Manager.
```

---

## ⏱️ 20:01 – 21:02 · 🧩 What Is a Package Manager?

🔑 **Key points**
- 🧰 A **package manager** is a **software tool** used by developers to:
```
  📦 PACKAGE MANAGER
   ├── 📥 download
   ├── 🧩 install
   ├── 🔄 update
   └── 🗑️ remove
        … any LIBRARY required for a project, with simple commands
```
- 🐢 Without one, it is *"a lengthy process"* of handling libraries yourself.
- 🎬 **Seen on screen** (typed 20:15 – 21:03):
```text
- Package Manager is a software tool used by developers to download, install,
  update or remove any library required for project.
```

🧠 **Hook:** *Package manager = download · install · update · remove libraries by command.*

---

## ⏱️ 21:02 – 22:02 · 🧩 Many Package Managers; NPM Comes With Node.js

🔑 **Key points**
- 🗂️ Package managers named in class:
```
  Yarn · Bower · Composer · NuGet · RubyGems · NPM
```
- 🎬 **Seen on screen** (typed 21:03 – 22:15, in this order). "RubyGEMS" is the instructor's spelling `[sic]`; the usual spelling is RubyGems:
```text
- There are various package managers like
     - Yarn
     - Bower
     - Composer
     - NuGet
     - RubyGEMS
     - NPM etc.
```
- 🎁 When you install **Node.js**, **one package manager comes by default**: **NPM**.

```
  🟢 Install Node.js ──► 📦 NPM installed automatically
```

---

## ⏱️ 22:02 – 23:41 · 🧩 Example: You Need Bootstrap

🔑 **Key points**
- 🌐 Suppose you build a web application in **any** technology (Java, .NET…) and want **icons, styles**.
- 🅱️ The usual library is **Bootstrap**: build **attractive, responsive websites**. *"Almost mandatory in every software technology."*
- 🎨 Any web-related developer must know **Bootstrap / Tailwind-like** concepts.
- 🌐 The "old way" starts with: visit the Bootstrap website → click **Download**.
- 🎬 **Seen on screen:** he types `getbootstrap.com` in the address bar (22:45). The home page (23:31, version menu shows v5.3) reads:
```text
Build fast, responsive sites with Bootstrap

Powerful, extensible, and feature-packed frontend toolkit. Build and customize
with Sass, utilize prebuilt grid system and components, and bring projects to life
with powerful JavaScript plugins.
```

---

## ⏱️ 23:41 – 23:59 · 🧩 Classroom Aside 🚫

> 🚫 **Non-technical.** A brief word to a student in class ("Be careful").

---

## ⏱️ 23:59 – 24:35 · 🧩 The Manual Way Is Risky ❌

🔑 **Key points**
- 🗜️ Downloaded files come as a **ZIP**. Then you must:
```
  🗜️ Unzip ──► 📋 Copy ──► 📁 Go to project ──► ➕ Create folder ──► 📌 Paste ──► 🛤️ Set the path ──► ✅ Use
```
- ⚠️ *"It's a very risky process."* Modern-technology developers don't do this.
- 🎬 **Seen on screen** (23:59 – 24:31): the Bootstrap download page, with the pointer on its **Download** button. The link shown in the browser's status bar confirms the download is a ZIP:
```text
Page:  https://getbootstrap.com/docs/5.3/getting-started/download/
Link:  https://github.com/twbs/bootstrap/releases/download/v5.3.8/bootstrap-5.3.8-dist.zip
```
- 🎬 The same page's "On this page" menu already lists **Package managers: npm · yarn · Bun · RubyGems · Composer · NuGet** (used in P5).

🧠 **Hook:** *Manual download = unzip, copy, paste, set path. Package manager = one command.*

---

## ✅ Quick Recall

```
  ☐ Expand NPM
  ☐ 4 jobs of a package manager
  ☐ Name 5 other package managers from class
  ☐ Which package manager comes with Node.js?
  ☐ Why do web devs need Bootstrap (as taught)?
  ☐ The 6 manual steps that NPM saves you
```
