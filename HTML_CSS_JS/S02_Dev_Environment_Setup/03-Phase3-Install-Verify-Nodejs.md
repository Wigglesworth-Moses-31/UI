# 3️⃣ Phase 3 · Install Node.js and Verify the Versions

**⏱️ 11:58 – 19:38** · 📂 S02 Dev Environment Setup · [⬅️ Prev](02-Phase2-What-Is-Nodejs.md) · [Next ➡️](04-Phase4-NPM-Package-Managers.md)

---

## ⏱️ 11:58 – 13:15 · 🧩 Which File to Download? 📦

🔑 **Key points**

| 💻 OS | 📦 Installer file |
|---|---|
| 🪟 Windows | **`.msi`** (Microsoft Installer) |
| 🍎 Mac / Unix / Linux / others | **`.pkg`** (package file) |

- 🧠 The website is **"intelligent enough"**: it **detects your OS** and offers the right download.
- 🔁 If it doesn't: Windows → **MSI**, Mac → **package**.
- 🎬 **Seen on screen** (typed in the notes file, 12:31 – 13:01):
```text
b) Download Node JS for your device
     [windows =>  .msi ]
     [Mac => .pkg ]
```

---

## ⏱️ 13:15 – 14:44 · 🧩 Demo: nodejs.org → Get Node.js 🛠️

🔑 **Key points**
- 📖 The site's own description: a **free, open-source, cross-platform JavaScript runtime environment** for creating servers, web apps, command-line tools and scripts.
- 🖱️ Click **Get Node.js** → it shows the **"macOS Installer (.pkg)"** button on the instructor's Mac (auto-detected).
- 🪟 On Windows it offers the **MSI**. ❌ **Don't download the second option: that is a ZIP file.** ✅ Download the **MSI**.
- 🎬 **Seen on screen** (14:01 home page `https://nodejs.org/en`, then 14:49 `https://nodejs.org/en/download`):
```text
Home page
  Run JavaScript Everywhere
  Node.js® is a free, open-source, cross-platform JavaScript runtime environment
  that lets developers create servers, web apps, command line tools and scripts.
  [ Get Node.js® ]

Download page
  Or get a prebuilt Node.js® for [macOS] running a [ARM64] architecture.
  [ macOS Installer (.pkg) ]   [ Standalone Binary (.gz) ]

  Link behind the first button:
  https://nodejs.org/dist/v24.16.0/node-v24.16.0.pkg
```
- 🎬 On the Mac page the second button is **Standalone Binary (.gz)**. The Windows page (MSI and ZIP) is described aloud only; it is never shown.
- 🎬 The code box above the buttons on the download page ends with the same two checks taught at 16:41:
```bash
node -v # Should print "v24.16.0".
npm -v # Should print "11.13.0".
```

```
  nodejs.org ──► [Get Node.js] ──► OS detected
                                     ├── 🍎 Mac      → .pkg  ✅
                                     └── 🪟 Windows  → .msi  ✅   (.zip ❌)
```

🧠 **Hook:** *Windows → MSI, not ZIP.*

---

## ⏱️ 14:44 – 16:41 · 🧩 Run the Installer

🔑 **Key points**
- ▶️ When the download completes, **open the downloaded file**: it runs the installer.
- ✅ *"Nothing complicated"*: **Continue → agree to the terms → Install** (Mac asks for your **password**).
- 🗑️ After "installation completed", the instructor moves the installer file to the bin (no longer needed).
- 🎬 **Seen on screen:** the downloaded file is `node-v24.16.0.pkg`, opened from the browser's Downloads list (15:03). The "Install Node.js" window has the steps Introduction → Licence → Destination Select → Installation Type → Installation → Summary. Its Summary page (15:39) reads:
```text
The installation was completed successfully.

This package has installed:
  •  Node.js v24.16.0 to /usr/local/bin/node
  •  npm v11.13.0 to /usr/local/bin/npm

Make sure that /usr/local/bin is in your $PATH.
```
- 🎬 On Close, macOS asks *Do you want to move the "Node.js" Installer to the Bin?* with **Keep** / **Move to Bin**; the instructor clicks **Move to Bin** (15:45).
- 🎬 He then types the steps into the notes file (16:21 – 16:57). The letters jump from d) to f) `[sic]`; there is no e):
```text
c) Open the downloaded file
d) Follow the process with "continue"
f) Finish installing by agreeing the terms.
```

```
  📥 Download package ──► 📂 Open it ──► ▶️ Continue ──► 📜 Agree terms ──► ✅ Install ──► 🏁 Finish
```

---

## ⏱️ 16:41 – 18:33 · 🧩 Check the Versions in the Terminal ⭐

🔑 **Key points**
- 🪟 Windows → **Command Prompt** (search for it in programs). 🍎 Mac → **Terminal**.
- ⌨️ Run these two commands:
```bash
node -v
npm -v
```
- 🔤 *"Capitalization, spellings, everything matters"*, including the **space** in `node -v`.
- 🐞 Beginners' most common complaint ("it's not working") comes from **spelling, capitalization, missing or extra spaces**.

> 🎬 **Seen on screen:** the transcript also writes "node-v", but both the typed notes and the terminal show the command **with a space**: **`node -v`** (as the instructor stresses at 18:01).

- 🎬 Typed in the notes file (17:29 – 18:01). The `>` stands for the prompt; you don't type it:
```text
- Check the version from your terminal / command prompt

     > node  -v
     > npm   -v
```
- 🎬 The instructor's Terminal (`node -v` at 19:13, `npm -v` by 19:39; his prompt is a plain `>`):
```text
>node -v
v25.9.0
>npm -v
11.12.1
```

---

## ⏱️ 18:33 – 19:38 · 🧩 Which Versions Are OK? ⭐

🔑 **Key points**

| 🔧 Tool | ✅ Required (as taught) | 👀 Instructor's machine |
|---|---|---|
| 🟢 Node | **20+** | 25 (🎬 terminal prints `v25.9.0`) |
| 📦 NPM | **10+** | 11 (🎬 terminal prints `11.12.1`) |

- 🎬 **Shown, not explained:** the installer run a few minutes earlier reported **Node.js v24.16.0** and **npm v11.13.0**, yet the terminal prints **v25.9.0** and **11.12.1**. The lecture does not comment on the difference.

> ⚠️ **Accuracy note:** `node -v` reports whichever `node` your shell finds first on its `PATH`. A machine that already has another Node.js installation can therefore print a different version from the one just installed. On a fresh machine you should see the version you installed.

- ⚠️ Developers who installed Node.js **years ago** may have an old version. **Below 20 → update / install the latest.** Older versions *"are not suitable for current generation"* development.

🧠 **Hook:** *Node 20+, NPM 10+.*

---

## 🛠️ Try it

```
  1. Open nodejs.org → Get Node.js → download the installer for your OS (.msi / .pkg)
  2. Open the downloaded file → Continue → agree → Install → Finish
  3. Open Command Prompt / Terminal and run:  node -v   and   npm -v
  4. Confirm Node ≥ 20 and NPM ≥ 10; if lower, install the latest
```

---

## 💻 Complete Code

```bash
# Check that Node.js and NPM are installed (Command Prompt / Terminal)
node -v    # should print 20 or higher
npm -v     # should print 10 or higher
```

> 🎬 **Seen on screen:** both commands are typed and run exactly like this; the instructor's output was `v25.9.0` and `11.12.1`.

---

## ✅ Quick Recall

```
  ☐ Windows installer extension? Mac installer extension?
  ☐ Which Windows download must you NOT pick?
  ☐ The 2 version commands, typed exactly
  ☐ Minimum Node version · minimum NPM version
  ☐ Most common beginner mistake when typing commands
```
