# 🛠️ Session 02 · Development Environment Setup

**🎓 Track:** Frontend Development · UI Full Stack with React.js (Naresh IT)
**📂 Course:** Frontend Dev · Session 02 / 66
**🎬 Type:** Practical setup + demos · ⏱️ ~70 min (00:11 – 1:10:18) · 💻 Little code (terminal commands, URLs, one AI prompt)
**👥 Speaker:** 🅢 **Sudhakar Sharma**
**📜 Transcript:** [../Session/Session_02.vtt](../Session/Session_02.vtt)
**🎬 Video check:** these notes were checked against the lecture's screen recording on 2026-11-14. 🎬 marks what was seen on screen. Frame-by-frame record: [Frames/Visual-Notes.md](Frames/Visual-Notes.md)
**💡 Why it matters:** Nothing in the course runs without this setup: **Node.js + NPM**, **VS Code + extensions**, and the **design/AI accounts** used daily. It also gives interview-ready definitions (Node.js, NPM, package manager, IDE) and the UI vocabulary (hero banner, cards, carousel, off-canvas) you need to prompt AI tools well.

---

## 🧭 Lecture at a Glance

```
 🔁 Recap S01 (generations · principles) ──► 🎯 today: set up YOUR DEVICE         (P1)
   │
   ▼
 ① 🟢 NODE.JS   JavaScript runtime · free · open source                            (P2)
   │            nodejs.org → .msi / .pkg → install → node -v (20+) · npm -v (10+)  (P3)
   │
   ├─ 📦 NPM    Node Package Manager: download · install · update · remove         (P4)
   │            npm install bootstrap · npm update bootstrap                       (P5)
   ▼
 ② 🧰 VS CODE   editor = IDE (build · debug · test · deploy) · free · MS · x-plat  (P6)
   │
 ③ 🧩 EXTENSIONS  Live Server · VS Code Icons · Live Preview · IntelliSense CSS    (P7, P8)
   │
 ④ 👤 ACCOUNTS  GitHub · Magnific · Canva · Copilot · Stitch with Google          (P9)
   │
   ▼
 🧵 STITCH DEMO  prompt ──► generated UI ──► WE hand-code it (no AI code)          (P10)
   │            UI words: header · hero banner · cards · footer ·
   │                      carousel · off-canvas · user dashboard                    (P10, P11)
   ▼
 ⏭️ Next: create a project (files · folders · run)                                  (P12)
```

---

## 🗺️ Phase Map

| # | ⏱️ Time | 🧩 Phase | 🏷️ Type | 📄 File |
|---|---|---|---|---|
| 1️⃣ | 00:11 – 05:48 | Recap & today's goal: set up your device | 🧠 Tech (04:34–05:48 🚫) | [01-Phase1-Recap-Setup-Roadmap.md](01-Phase1-Recap-Setup-Roadmap.md) |
| 2️⃣ | 05:48 – 11:58 | What is Node.js and why install it? | 🧠 Tech (09:01–11:03 🚫) | [02-Phase2-What-Is-Nodejs.md](02-Phase2-What-Is-Nodejs.md) |
| 3️⃣ | 11:58 – 19:38 | Install Node.js and verify versions | 🧠 Tech · 💻 | [03-Phase3-Install-Verify-Nodejs.md](03-Phase3-Install-Verify-Nodejs.md) |
| 4️⃣ | 19:38 – 24:35 | NPM & package managers | 🧠 Tech | [04-Phase4-NPM-Package-Managers.md](04-Phase4-NPM-Package-Managers.md) |
| 5️⃣ | 24:35 – 30:31 | NPM in action: install & update Bootstrap | 🧠 Tech · 💻 | [05-Phase5-NPM-In-Action-Bootstrap.md](05-Phase5-NPM-In-Action-Bootstrap.md) |
| 6️⃣ | 30:31 – 37:13 | Visual Studio Code editor (IDE) | 🧠 Tech | [06-Phase6-VS-Code-Editor.md](06-Phase6-VS-Code-Editor.md) |
| 7️⃣ | 37:13 – 41:16 | Install VS Code extensions | 🧠 Tech | [07-Phase7-VS-Code-Extensions.md](07-Phase7-VS-Code-Extensions.md) |
| 8️⃣ | 41:16 – 46:32 | Why each extension? | 🧠 Tech | [08-Phase8-Why-Each-Extension.md](08-Phase8-Why-Each-Extension.md) |
| 9️⃣ | 46:32 – 53:19 | Accounts: GitHub, Magnific, Canva, Copilot, Stitch | 🧠 Tech | [09-Phase9-Accounts-To-Create.md](09-Phase9-Accounts-To-Create.md) |
| 🔟 | 53:19 – 1:02:01 | Stitch with Google & prompting with technical names | 🧠 Tech (54:01–56:59 🚫) | [10-Phase10-Stitch-And-Prompting.md](10-Phase10-Stitch-And-Prompting.md) |
| 1️⃣1️⃣ | 1:02:01 – 1:06:40 | The design plan & UI vocabulary | 🧠 Tech | [11-Phase11-Design-Plan-UI-Vocabulary.md](11-Phase11-Design-Plan-UI-Vocabulary.md) |
| 1️⃣2️⃣ | 1:06:40 – 1:10:18 | Wrap-up: next step & logistics | 🚫 Mostly non-tech | [12-Phase12-Wrap-Up.md](12-Phase12-Wrap-Up.md) |

---

## 🎯 Interview Hot-Spots (flagged by the speaker)

```
  ⭐ Define Node.js → JavaScript runtime, free, open source           P2 · 06:10
  ⭐ "Why install Node.js?" → to build web applications               P2 · 08:44
  ⭐ What is NPM / a package manager? (download·install·update·remove) P4 · 19:38
  ⭐ Expand IDE + what an editor provides                             P6 · 32:01
  ⭐ Why run pages from a server (Live Server), not by double-click   P8 · 41:16
  ⭐ Know UI technical names: hero banner · cards · carousel · off-canvas  P10–P11
```

---

## 🛠️ Tasks Assigned (keep ready before the next session)

```
  ☐ Install Node.js (20+) from nodejs.org → check  node -v  and  npm -v (10+)     P3
  ☐ Install VS Code from code.visualstudio.com                                    P6
  ☐ Install extensions: Live Server (Ritwick Dey) · VS Code Icons ·
     IntelliSense for CSS class names in HTML · Live Preview                      P7
  ☐ Create accounts: GitHub · Magnific · Canva · Microsoft Copilot ·
     Stitch with Google                                                           P9
```

---

## 📓 Keyword Notebook

| 🔑 Keyword | ⏱️ First heard | 💬 In this lecture | 🗣️ Transcript wrote |
|---|---|---|---|
| Development environment | 02:23 | Setting up your device to build web apps | |
| Windows 8+ | 04:05 | Minimum Windows stated (see P1 accuracy note) | |
| Node.js | 04:46 | JavaScript runtime; free, open source | |
| nodejs.org | 06:04 | Official Node.js website | |
| JavaScript runtime | 06:21 | What Node.js is | |
| Server (build vs use) | 07:21 | Node.js lets you build your own server | |
| Command-line tools · command prompt | 07:59 | Tools like Windows command prompt | |
| Server-side scripts | 08:16 | Another Node.js use | |
| `.msi` (Microsoft Installer) | 12:29 | Windows installer file | |
| `.pkg` | 12:38 | Mac/other installer package | |
| Cross-platform | 13:43 | Node.js and VS Code both | |
| Terminal · Command Prompt | 17:06 | Where version commands run | |
| `node -v` · `npm -v` | 17:37 | Check installed versions | "node-v" |
| NPM | 17:42 | Node Package Manager | |
| Package manager | 20:01 | Download · install · update · remove libraries | |
| Library | 20:28 | Reusable code a project needs | |
| Yarn · Bower · Composer · NuGet · RubyGems | 21:12 | Other package managers (+ Bun on Bootstrap's site, 26:50) | |
| Bootstrap · Tailwind | 22:38 | Library for attractive, responsive sites | |
| Path (set the path) | 24:29 | Manual setup step NPM avoids | |
| `npm install bootstrap` | 25:18 | Install a library with one command | "NPM install and Bootstrap" |
| `npm update bootstrap` | 26:12 | Update to latest version | |
| Visual Studio Code | 30:47 | Our editor; code.visualstudio.com | |
| Editor | 31:58 | Tool that provides an IDE | |
| IDE | 32:13 | Integrated Development Environment | |
| Build · debug · test · deploy | 32:34 | What an IDE lets you do | |
| Visual Studio | 35:47 | Heavy IDE for .NET / Azure; not needed | |
| Extensions | 37:35 | Make VS Code ready for a technology | |
| Live Server | 39:41 | Run pages from a local server | |
| Ritwick Dey | 39:56 | Live Server author | "Ritwik Dey" |
| VS Code Icons | 40:06 | File-type icons | |
| IntelliSense for CSS class names in HTML | 40:17 | Suggestions while typing | |
| Live Preview | 40:58 | Preview while designing | |
| GitHub · versioning tool | 47:20 | Deploy, share, collaborate, release versions | |
| Magnific | 47:59 | Icons, images, videos for web design | "Magnifica" |
| Canva | 48:25 | Design resources; free account | "Canvas" |
| Stitch with Google | 48:54 | AI tool that generates UI previews | |
| Copyright | 50:38 | Why not to use Googled images | |
| Microsoft Copilot | 52:15 | AI generation, incl. images | |
| Quantum computing | 55:09 | 🚫 instructor's "future of computers" view | |
| Generative AI · prompt engineering | 57:18 | How to talk with AI for exact results | |
| Cards | 58:22 | Product boxes | "carts" |
| Footer | 58:25 | Bottom section | |
| Header | 59:40 | Bar at the top of a page | |
| Hero banner | 59:57 | Big image area at the top | |
| User dashboard | 1:03:13 | Page after sign-in | |
| Carousel | 1:05:21 | Sliding banners (Amazon) | |
| Off-canvas | 1:06:16 | Pop-out menu panel (🎬 typed on screen as "Offcanvas") | |

---

## 🚫 Non-Technical Segments

```
  04:34 – 05:48     "keep it ready by tomorrow" practice warning (step ① itself is technical)
  09:01 – 11:03     make-notes rant
  23:41 – 23:59     brief classroom aside
  54:01 – 56:59     "AI is a bubble" opinion, Microsoft/IBM/TCS claims (as said)
  1:07:19 – 1:10:18 pace, WhatsApp/Drive notes, videos, schedule
  1:10:18 – end     silence + unrelated non-English audio (not part of the lecture)
```

---

## ⚠️ Accuracy Notes Added

- **P1** · current Node.js (20+) officially supports **Windows 10+**, not Windows 8.
- **P3** · `node -v` prints the first `node` on your `PATH`, so it can differ from the version just installed (🎬 installer said v24.16.0, terminal printed v25.9.0).
- **P5** · a specific version is installed as `npm install bootstrap@<version>`; on screen he typed only `bootstrap@vers` and deleted it.
- **P6** · the "website of editors" shown is editorconfig.org, the EditorConfig project, not a directory of all editors.
- **P11** · "Offcanvas" is Bootstrap's name; the same part is also called a drawer or side panel.

---

## ✅ Lecture Recall

```
  ☐ The 4 setup steps, in order
  ☐ Define Node.js · 4 things you can build with it · why we install it
  ☐ Windows vs Mac installer file; the download NOT to pick
  ☐ Version commands + minimum versions (Node 20+, NPM 10+)
  ☐ Expand NPM · 4 jobs of a package manager · 2 Bootstrap commands
  ☐ Expand IDE · 4 reasons for VS Code · VS vs VS Code
  ☐ 4 extensions + the purpose of each
  ☐ 5 accounts + why GitHub and why Magnific
  ☐ Stitch: what we use it for and what we don't
  ☐ 7 UI technical names from the demo
```

---
⏭️ **Next session (per 1:06:53 and 1:09:48):** create a project: add files and folders and run it, along with the instructor (Monday).
