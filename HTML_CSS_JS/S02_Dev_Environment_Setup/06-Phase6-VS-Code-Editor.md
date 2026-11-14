# 6️⃣ Phase 6 · Step ②: Visual Studio Code Editor

**⏱️ 30:31 – 37:13** · 📂 S02 Dev Environment Setup · [⬅️ Prev](05-Phase5-NPM-In-Action-Bootstrap.md) · [Next ➡️](07-Phase7-VS-Code-Extensions.md)

---

## ⏱️ 30:31 – 31:20 · 🧩 Second Step: Install VS Code

🔑 **Key points**
- 🧰 Once the device is ready with Node.js: **download and install the Visual Studio Code editor**.
- 🎬 **Seen on screen** (typed by 30:59, in bold, under the version note):
```text
2. Download and Install Visual Studio Code Editor
```

---

## ⏱️ 31:20 – 32:01 · 🧩 Why Not Just Notepad?

🔑 **Key points**
- 📝 Can you **write** Java, .NET, C, C++ programs in **Notepad**? ✅ Yes.
- ⚙️ Can you **compile** them from Notepad? ❌ No. **Run** them? ❌ No.
- 🧩 A developer needs different environments for **building, debugging, testing, deploying**.

---

## ⏱️ 32:01 – 33:08 · 🧩 Editor = IDE ⭐🎯

🔑 **Key points**
- 🧰 An **editor** is a software tool that provides an **integrated development environment**.
- 🔤 **IDE = Integrated Development Environment**.
```
  🧰 IDE (one place)
   ├── 🏗️ build
   ├── 🐞 debug   (identify bugs, fix them)
   ├── 🧪 test
   └── 🚀 deploy
```
- 🎬 **Seen on screen** (typed 32:29 – 33:03):
```text
- Editor provides an IDE for developer.
- Integrated Development Environment for building, debugging, testing & deploying.
```

🧠 **Hook:** *IDE = build · debug · test · deploy, from one place.*

---

## ⏱️ 33:08 – 34:24 · 🧩 Many Editors, Many Paid

🔑 **Key points**
- 🌍 VS Code is enough for **any technology**, begin to end: Java, .NET, Python; Angular, React, Vue.
- 📚 The instructor shows a website listing editors: *"hundreds of editors"*, each with different features.
- 💰 **Many editors are paid**, not free.
- 🎬 **Seen on screen** (33:47 – 34:57): the website is `https://editorconfig.org`. The instructor scrolls its wall of editor logos, under the page's line *"These editors come bundled with native support for EditorConfig. Everything should just work."* Logos readable in the frames:
```text
BBEdit · Code Crusader · CodeLite · elementary Code · EmEditor · Builder · Gitea
Helix · IntelliJ IDEA · jdTextEdit · KTextEditor · Komodo · Kakoune
Visual Studio | MonoDevelop · Neovim · Nova · PhpStorm · PyCharm · ReSharper
Sublime Text · Textadept · textmate · VSCodium · Visual Studio Code
```
- 🎬 He stops with the pointer on the **Visual Studio Code** logo (34:57), the last one in that group.

> ⚠️ **Accuracy note:** editorconfig.org is the home of the **EditorConfig** project (one shared file that keeps coding style consistent across editors). Its logo wall lists editors and tools that support EditorConfig; it is not an official directory of all code editors. It still makes the point that there are a great many editors.

---

## ⏱️ 34:24 – 35:05 · 🧩 Why VS Code? ⭐

| ✅ Reason (as taught) |
|---|
| 🏢 It is from **Microsoft** |
| 🆓 It is **free** |
| 🖥️ It is **cross-platform** |
| 🧩 It provides good **extensions** for any technology |

🧠 **Hook:** *Microsoft · free · cross-platform · extensions.*

---

## ⏱️ 35:05 – 35:44 · 🧩 Download Location

🔑 **Key points**
- 🌐 Official website (🎬 the address typed on screen is the **download page**, not the home page):
```text
https://code.visualstudio.com/download
```
- 📥 Download and install it **the same simple way** as Node.js.
- 🎬 **Seen on screen** (typed in the notes file by 35:47):
```text
a) Visit "https://code.visualstudio.com/download"

b) Download and Install VSCode
```

---

## ⏱️ 35:44 – 36:16 · 🧩 Visual Studio ≠ Visual Studio Code ⚠️

| | 🟪 Visual Studio | 🟦 Visual Studio Code |
|---|---|---|
| 👥 For | Microsoft technologies (**.NET, Azure**) | Us: any technology |
| ⚖️ Weight | **Very heavy**, complex | **Lightweight, fast, simple** |
| 👀 Looks | Similar name; *"logo also same"* (as said) | |
| ✅ Use in class? | ❌ Not required | ✅ Yes |

- 🎬 **Seen on screen:** this comparison is spoken only; nothing is typed for it. Both logos do appear on the editorconfig.org page shown earlier (34:09 and 34:57): the same ribbon shape, **purple** for Visual Studio and **blue** for Visual Studio Code.

---

## ⏱️ 36:16 – 37:13 · 🧩 Install & Check

🔑 **Key points**
- 💻 Download for **your OS**, then *next, next, next, finish*.
- 👀 Already installed on the instructor's device, so he says he doesn't need to download it again (but see the 🎬 note below).
- ✅ Checkpoint: **Node.js** and **VS Code** are both ready.
- 🎬 **Seen on screen** (36:29 – 36:37), the page `https://code.visualstudio.com/download`:
```text
Download Visual Studio Code
Free and built on open source. AI agents, Git, debugging, and extensions included.

[ Windows ]        [ .deb ]            [ .rpm ]                 [ Mac ]
 Windows 10, 11     Debian, Ubuntu      Red Hat, Fedora, SUSE    macOS 12.0+

Windows also lists: User Installer · System Installer · .zip · CLI
Mac also lists:     .dmg (Intel chip · Apple silicon · Universal) · CLI
```
- 🎬 **Shown, differs from what is said:** although he says "I'm not downloading", at 36:37 the pointer is on the **Mac** button and at 36:47 the browser is on VS Code's "Thanks for downloading" page (`code.visualstudio.com/thank-you?dv=osx`), so the button was clicked. At 36:55 the tab shows the release notes **Visual Studio Code 1.124** (release date June 10, 2026). No installer for VS Code is opened in the frames.

---

## 🛠️ Try it

```
  1. Open code.visualstudio.com/download
  2. Download the build for your operating system
  3. Run the installer: next → next → finish
  4. Make sure it's "Visual Studio Code", not "Visual Studio"
```

---

## ✅ Quick Recall

```
  ☐ Notepad: can write? compile? run?
  ☐ Expand IDE + its 4 jobs
  ☐ 4 reasons to choose VS Code
  ☐ VS Code download URL
  ☐ Visual Studio vs Visual Studio Code: who is each for?
```
