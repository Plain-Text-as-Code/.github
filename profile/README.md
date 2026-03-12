# 📄 The Plain Text as Code Manifest

> *A philosophy for structuring software knowledge in an agentic AI age*

---

## 💡 Inspiration

The rise of *Infrastructure as Code* and *Architecture as Code* proved a simple truth:  
when knowledge lives as plain text in version control, it becomes permanent, portable, and actionable.

Plain Text as Code extends that idea to everything.

---

## 🏅 We Value

**📝 Plain text over proprietary tools**  
Tools lock knowledge away. Plain text is universal, versionable, and readable by humans and AI alike.  
Plain text formats are files you can open in any editor and read directly: `.txt`, `.md`, `.adoc`, and similar.  
XML-based formats like XDOC are not plain text — they wrap content in markup that must be parsed before the content is accessible.

**📁 File structure over navigation systems**  
A well-organized repo is its own documentation. Let the structure speak.

**⚙️ Generated output over stored binaries**  
Plain text is the source. Binaries are the result. Version the source, not the artifact.

**🎯 Content over presentation**  
Binary and proprietary formats embed layout, style, and metadata that serve only visualization — not the content itself.  
Plain text carries only the substance.

**🗺️ Plain text diagrams over visual drawing tools**  
Diagram formats like Mermaid and D2 capture semantics, not pixels.  
A PNG or a proprietary diagram file contains only rendered shapes with no accessible meaning.  
When a plain text diagram format is not suitable, ASCII or ANSI diagrams are the best fallback — they stay readable in any context and require no tooling to interpret.

**🌐 Unicode as the default character set**  
Unicode covers every human language, technical symbol, and emoji in a single, universally supported encoding.  
It lets you embed meaning directly in the text — arrows (→), checkmarks (✓), warning signs (⚠️), category markers (📁), and status indicators (🔴🟡🟢) — without any markup, images, or workarounds.  
A symbol or emoji inline is just a character: diffable, searchable, copyable, and expressive without visual overhead.

**🖼️ Symbols and emojis over lengthy descriptions**  
A picture is worth a thousand words — and so is the right symbol or emoji.  
Use them deliberately to convey status (✅ ❌ ⚠️), direction (→ ↑ ↓), category (📦 🔧 📖), or emphasis (🚨 💡 🎯).  
They compress meaning without losing it, making content faster to scan for humans and no harder to process for AI.  
Use them wisely: a well-chosen symbol clarifies; an overused one clutters.

**🔩 Battle-tested primitives over custom infrastructure**  
Use what everyone already knows: Git, Markdown, zip. No learning curve, no lock-in.

---

## 📐 Core Principles

### 1. 🔄 X as Code
Infrastructure as Code. Architecture as Code. Documentation as Code.  
Whatever your domain — express it as plain text, version it, and let tools consume it.

### 2. 📦 Binaries are output, not source
Binary and proprietary formats contain meta information, layout, and style that only contribute to visualization, not to the actual content.  
Extracting meaning requires parsing and filtering through all of that overhead.  
Plain text carries just the content — no noise, no hidden structure, nothing to strip away.  
Generated files belong outside version control. Regenerate them from source when needed.  
When a binary has no reproducible source, pragmatism wins over purity.

### 3. 🗃️ One repo, one source of truth
All code and knowledge for a system live together.  
If it's not in the repo, it doesn't exist.

### 4. 🧭 File structure is navigation
The file system is your information architecture — free, universal, always up to date.  
Add a `README.md` where it adds value: in documentation folders as the index, and in modules or sub-projects to explain what they contain.  
Git vendors render it automatically. Code folders speak for themselves.

### 5. 🛠️ Use what already works
Prefer universally understood, battle-tested tools over custom solutions.  
Git for history. Markdown for prose. Mermaid or D2 for diagrams. Zip for packaging.  
The best tool is the one that needs no explanation.

### 6. 🤖 AI-first structure
Design your repo so AI agents can read and act on it without human translation.  
Structured plain text is what AI understands natively.

---

## ✅ Why It Works

**🏛️ It survives tool rot.** Wikis go stale. A Markdown file in a git repo is forever.

**🤖 It scales with AI.** The more structured your repo, the more capable your AI toolchain becomes.

**⚡ It removes friction.** No tools to install, no dashboards to configure, no licenses to manage.

**🔍 It forces clarity.** If you can't express it as plain text, you haven't thought it through yet.

---

---

## 🔧 Start Here

A [`.gitattributes`](../../.gitattributes) starter file is included in this repo.  
It enforces LF line endings and UTF-8 encoding for all plain text files — keeping your repo consistent across editors, OSes, and contributors.

---

*Plain Text as Code is not a framework. It is a mindset.*  
*Structure your knowledge well, and everything else follows.*

*✊ I am a Plain Text Coder.*
