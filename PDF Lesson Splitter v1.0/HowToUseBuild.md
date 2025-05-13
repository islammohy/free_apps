# PDF Lesson Splitter v1.0 (Free Edition)

Feed the app one big PDF and a simple list of page numbers; it instantly chops the file into neatly numbered lesson PDFs. Perfect for teachers, trainers, and anyone who needs to hand out just the right pages without fussing with Acrobat.

---

## 🌟 At a Glance

| ✔  | Feature                                                                                            |
| -- | -------------------------------------------------------------------------------------------------- |
| 📄 | **One‑click splitting** – pick your PDF, import a CSV of page breaks, press **Split!**             |
| 📂 | **Batch‑ready** – slices the entire document in seconds, saving each lesson in a folder you choose |
| 🛑 | **Non‑destructive** – original PDF stays intact                                                    |
| 💾 | **Smart naming** – outputs `MyBook_1‑5.pdf`, `MyBook_6‑10.pdf`, etc.                               |
| 🏷 | **CSV or TXT** – breakpoints can be comma‑, space‑, or line‑separated                              |

---

## Preparing Your Breakpoints

Create a plain‑text file (CSV or TXT) that lists the **first page** of every new lesson.

Example (`index.csv`) for a 30‑page book split into six 5‑page lessons:

```
1,6,11,16,21,26
```

*(The last range is automatic; no need to type “31”.)*

---

## 🪟 Windows (.exe)

1. **Download**
   Get **`PDF‑Lesson‑Splitter‑win‑v1.0.zip`** from the latest GitHub release.

2. **Unzip**
   Right‑click → **Extract All…**. Inside you’ll see **`PDF‑Lesson‑Splitter.exe`**.

3. **Run**
   Double‑click the **.exe**.
   If SmartScreen appears, click **More info → Run anyway** (the app is safe but unsigned).

4. **Split Your PDF**

   1. Click **Browse PDF…** and choose your source file.
   2. Click **Import Breakpoints…** and select your **index.csv**.
   3. Click **Browse Output Folder…** and pick where the smaller PDFs should go.
   4. Hit **Split!** – watch the progress log. When it finishes, open the folder to find your lesson files.

> The app is fully portable; keep it on a USB stick for school‑lab use.

---

## 🍎 macOS (.app in .dmg)

1. **Download**
   Grab **`PDF‑Lesson‑Splitter‑mac‑v1.0.dmg`** from the release page.

2. **Install**

   * Double‑click the .dmg to mount it.
   * Drag **PDF Lesson Splitter.app** into **Applications** (or anywhere you like).

3. **First Launch**
   Because we’re outside the App Store, Gatekeeper shows a prompt the first time:
   *Right‑click the app → Open → Open.* You’ll only need to do this once.

4. **Split Your PDF**
   Follow the same four‑step flow as on Windows: **Browse PDF → Import Breakpoints → Choose Output Folder → Split!**

> Tested on macOS 12 (Monterey) through macOS 14 (Sonoma) on both Intel and Apple Silicon Macs.

---

## 🤔 FAQ

| Question                                              | Answer                                                                                                 |
| ----------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| **Does the CSV need headers?**                        | No. Just the numbers (e.g., `1,6,11…`).                                                                |
| **What if I type a page number larger than the PDF?** | It’s ignored; the app never crashes on bad input.                                                      |
| **Can I undo a split?**                               | Your original PDF is untouched. Simply delete the generated lesson files if you don’t want them.       |
| **Scanned PDFs supported?**                           | Yes — as long as the PDF opens normally, page extraction works the same.                               |
| **Where do I report issues?**                         | Open an *Issue* on the GitHub repo with your OS version, PDF length, and the breakpoint file you used. |

---

## 📄 License & Credits

Released under the **MIT License** – free for personal use.

Slice away and share the pages you need! ✂️📚
