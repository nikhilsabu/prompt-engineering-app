# 🎯 Prompt Engineering — Learn to Code Prompts

An interactive, self-contained web app to learn prompt engineering through lessons, quizzes, and a live sandbox analyzer.

**Live Demo:** `https://YOUR-USERNAME.github.io/prompt-engineering-app`

---

## 📦 What's Inside

```
prompt-engineering-app/
├── index.html      ← The entire app (no build step needed!)
└── README.md       ← This file
```

Everything runs in a **single HTML file** — no npm, no Node.js, no build tools required.

---

## 🚀 How to Host on GitHub Pages (Step-by-Step)

### Step 1 — Create a GitHub Account
If you don't have one: go to **https://github.com** → click **Sign up**

---

### Step 2 — Create a New Repository

1. Click the **+** button (top-right) → **New repository**
2. Repository name: `prompt-engineering-app`
3. Set visibility to **Public** ✅ (required for free GitHub Pages)
4. Check **"Add a README file"** ✅
5. Click **Create repository**

---

### Step 3 — Upload Your Files

**Option A — Upload via GitHub website (easiest):**
1. Open your new repository
2. Click **"Add file"** → **"Upload files"**
3. Drag and drop both `index.html` and `README.md`
4. Scroll down → click **"Commit changes"**

**Option B — Use Git on your computer:**
```bash
git clone https://github.com/YOUR-USERNAME/prompt-engineering-app.git
cd prompt-engineering-app
# Copy index.html and README.md into this folder
git add .
git commit -m "Add prompt engineering app"
git push origin main
```

---

### Step 4 — Enable GitHub Pages

1. In your repository, click **Settings** (top tab)
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **"Deploy from a branch"**
4. Branch: **main** | Folder: **/ (root)**
5. Click **Save**

---

### Step 5 — Visit Your Live Site

After ~1–2 minutes, your site will be live at:

```
https://YOUR-USERNAME.github.io/prompt-engineering-app
```

Replace `YOUR-USERNAME` with your actual GitHub username.

---

## 🔄 How to Update Your Site

Just edit `index.html` and push/upload again. GitHub Pages will auto-deploy within ~1 minute.

Via the GitHub website:
1. Click on `index.html` in your repo
2. Click the **pencil icon** (Edit)
3. Make changes → **Commit changes**

Via Git:
```bash
git add index.html
git commit -m "Update lessons"
git push
```

---

## 🧠 What the App Teaches

| Section  | What You Learn |
|----------|----------------|
| 📚 Learn  | 6 core prompt engineering techniques with weak vs. strong examples |
| 🧠 Quiz   | 4 multiple-choice questions with instant feedback |
| 🔬 Sandbox | Paste any prompt → get a quality score across 6 dimensions |

### The 6 Techniques Covered
1. **Be Specific & Clear** — Vague prompts yield vague results
2. **Assign a Role** — Shape tone and expertise with persona
3. **Few-Shot Examples** — Show the model what you want
4. **Chain of Thought** — Step-by-step reasoning reduces errors
5. **Constrain the Output** — Format control for structured data
6. **Iterative Refinement** — Prompt engineering as a feedback loop

---

## 🛠 Technical Notes

- Pure HTML + React (loaded via CDN) — no build step
- Works offline after first load
- Mobile responsive
- No backend, no API keys needed

---

## 📄 License

MIT — free to use, modify, and share.
