# 🌳 Branch Guide - Quest for the Python Crown

## ✅ All Branches Created and Ready!

This repository has **7 branches**:

### **Main Branch**
- **Branch:** `main`
- **Contains:** Full course overview, instructor notes, quickstart guide
- **Purpose:** Instructor reference and course information
- **For:** Instructors only

---

## 📚 Chapter Branches

### **Chapter 1: The Beginning**

#### Student Branch: `chapter-01-beginning`
- **Notebook:** `chapter_01_beginning.ipynb` (UNSOLVED)
- **README:** Chapter 1 specific instructions
- **Contains:** Theory, examples, 4 challenges + bonus (no solutions)
- **Release:** Week 1
- **For:** Students to work on

#### Solution Branch: `chapter-01-solution`
- **Notebook:** `chapter_01_beginning.ipynb` (SOLVED)
- **Contains:** Complete solutions with detailed explanations
- **Release:** Week 2 (after students complete)
- **For:** Students to review their work

---

### **Chapter 2: Choosing Your Path**

#### Student Branch: `chapter-02-control-flow`
- **Notebook:** `chapter_02_control_flow.ipynb` (UNSOLVED)
- **README:** Chapter 2 specific instructions
- **Contains:** Theory, examples, 4 challenges + bonus (no solutions)
- **Release:** Week 2
- **For:** Students to work on

#### Solution Branch: `chapter-02-solution`
- **Notebook:** `chapter_02_control_flow.ipynb` (SOLVED)
- **Contains:** Complete solutions with detailed explanations
- **Release:** Week 3 (after students complete)
- **For:** Students to review their work

---

### **Chapter 3: The Journey Continues**

#### Student Branch: `chapter-03-loops`
- **Notebook:** `chapter_03_loops.ipynb` (UNSOLVED)
- **README:** Chapter 3 specific instructions
- **Contains:** Theory, examples, 4 challenges + bonus (no solutions)
- **Release:** Week 3
- **For:** Students to work on

#### Solution Branch: `chapter-03-solution`
- **Notebook:** `chapter_03_loops.ipynb` (SOLVED)
- **Contains:** Complete solutions with detailed explanations
- **Release:** Week 4 (after students complete)
- **For:** Students to review their work

---

## 🎯 How to Use These Branches

### For Students (GitHub Method):

#### Week 1:
```bash
git clone https://github.com/YOUR-USERNAME/python-quest.git
cd python-quest
git checkout chapter-01-beginning
# Work on Chapter 1
```

#### Week 2:
```bash
# Review solution
git checkout chapter-01-solution

# Start new chapter
git checkout chapter-02-control-flow
# Work on Chapter 2
```

#### Week 3:
```bash
# Review solution
git checkout chapter-02-solution

# Start new chapter
git checkout chapter-03-loops
# Work on Chapter 3
```

### For Students (Google Colab Method):

1. **Download the notebook file** for the current chapter from GitHub
2. **Upload to Google Colab**
3. **Work through challenges**
4. **Check solutions** when released (download solution branch)

### For Instructors:

#### Releasing Chapters:
```bash
# Week 1: Release Chapter 1
# Students access: chapter-01-beginning

# Week 2: Release solution + new chapter
# Students can access: chapter-01-solution, chapter-02-control-flow

# Week 3: Release solution + new chapter
# Students can access: chapter-02-solution, chapter-03-loops

# Continue pattern...
```

---

## 📂 What's in Each Branch Type?

### Student Branches (`chapter-XX-beginning`, `chapter-XX-control-flow`, etc.)
```
├── README.md                    # Chapter-specific instructions
├── notebooks/
│   └── chapter_XX_*.ipynb      # Student notebook (UNSOLVED)
└── requirements.txt             # Dependencies
```

**Key Features:**
- ✅ Theory sections with explanations
- ✅ Interactive examples
- ✅ Challenge code cells with `# 👇 YOUR CODE HERE 👇`
- ✅ Test framework
- ✅ NO SOLUTIONS - students fill these in
- ❌ No instructor notes

### Solution Branches (`chapter-XX-solution`)
```
├── README.md                    # Same chapter instructions
├── notebooks/
│   └── chapter_XX_*.ipynb      # Instructor notebook (SOLVED)
└── requirements.txt             # Dependencies
```

**Key Features:**
- ✅ All theory and examples (same as student branch)
- ✅ Complete working solutions for all challenges
- ✅ Detailed explanations (💡 EXPLANATION comments)
- ✅ Common mistakes highlighted
- ✅ All test cells (they pass!)
- ❌ No instructor notes

### Main Branch (Instructor Reference)
```
├── README.md                    # Full course overview
├── INSTRUCTOR_NOTES.md          # Teaching guide
├── QUICKSTART.md               # Setup instructions
├── SOLUTION_EXAMPLE.md         # How to create solutions
├── BRANCH_GUIDE.md             # This file!
├── notebooks/
│   ├── chapter_01_beginning.ipynb
│   ├── chapter_02_control_flow.ipynb
│   └── chapter_03_loops.ipynb
└── requirements.txt
```

**Key Features:**
- ✅ Complete course outline (all 20 chapters)
- ✅ Instructor teaching notes
- ✅ Week-by-week schedule
- ✅ All notebooks (unsolved versions)
- ✅ Setup and distribution guides
- 🔒 Keep private or share with co-teachers only

---

## 🔍 Quick Verification Commands

### Check all branches exist:
```bash
git branch -a
```

**Expected output:**
```
  chapter-01-beginning
  chapter-01-solution
  chapter-02-control-flow
  chapter-02-solution
  chapter-03-loops
  chapter-03-solution
* main
```

### Check a specific branch:
```bash
git checkout chapter-01-beginning
ls notebooks/
# Should see: chapter_01_beginning.ipynb
```

### Check solutions are present:
```bash
git checkout chapter-01-solution
grep "# 👇 SOLUTION 👇" notebooks/chapter_01_beginning.ipynb
# Should find solutions in the file
```

---

## 🎨 Branch Naming Convention

We use descriptive names, not just numbers:

- `chapter-01-beginning` (not chapter-01)
- `chapter-02-control-flow` (not chapter-02)
- `chapter-03-loops` (not chapter-03)

This makes it **immediately clear** what each chapter teaches!

---

## 🚀 Pushing to GitHub

If you want to push all branches to GitHub:

```bash
# Add remote (replace with your URL)
git remote add origin https://github.com/YOUR-USERNAME/python-quest.git

# Push all branches
git push -u origin main
git push -u origin chapter-01-beginning
git push -u origin chapter-01-solution
git push -u origin chapter-02-control-flow
git push -u origin chapter-02-solution
git push -u origin chapter-03-loops
git push -u origin chapter-03-solution
```

Or push all at once:
```bash
git push -u origin --all
```

---

## ✅ Verification Checklist

Before releasing to students, verify:

### Chapter 1 Student Branch:
- [ ] Branch exists: `chapter-01-beginning`
- [ ] Contains: `chapter_01_beginning.ipynb`
- [ ] Challenges are UNSOLVED (no code in YOUR CODE HERE sections)
- [ ] Test framework is present
- [ ] No instructor files (no INSTRUCTOR_NOTES.md)
- [ ] README has chapter 1 info

### Chapter 1 Solution Branch:
- [ ] Branch exists: `chapter-01-solution`
- [ ] Contains: `chapter_01_beginning.ipynb`
- [ ] All 4 challenges have complete solutions
- [ ] Solutions have detailed explanations
- [ ] Bonus challenge has example solution
- [ ] All tests should pass when run

### Repeat for Chapters 2 and 3...

---

## 🎯 Distribution Strategies

### Option 1: GitHub (Recommended)
- Students clone repo
- `git checkout chapter-XX` to switch chapters
- Easy version control
- Clear history

### Option 2: Direct Download
- Students download notebook files directly
- Upload to Google Colab
- No git knowledge required
- Simpler for young students

### Option 3: Google Drive
- Upload notebooks to shared Drive
- Students make copies
- Organize by week folders
- Good for Chromebook users

---

## 📊 Student Progress Tracking

### Method 1: GitHub Forks
- Students fork your repository
- They push completed work
- You can see their commits

### Method 2: File Submission
- Students download completed notebooks
- Submit via Canvas/LMS
- You check against solution branch

### Method 3: In-Person Verification
- Students show passing tests in class
- You verify during lab time
- Immediate feedback

---

**All branches are ready! Your course is complete and ready to teach!** 🎉
