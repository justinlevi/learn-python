# 🚀 Quick Start Guide - Quest for the Python Crown

## For Students (Getting Started)

### Step 1: Access Google Colab
1. Go to [colab.research.google.com](https://colab.research.google.com)
2. Sign in with your Google account

### Step 2: Upload Chapter 1
1. Download `chapter_01_beginning.ipynb` from the repository
2. In Colab, click **File → Upload notebook**
3. Upload the file you downloaded

### Step 3: Start Learning!
1. Read each cell carefully
2. Run code cells with **Shift + Enter**
3. Complete the challenges
4. Run the test cells to check your work

### Step 4: Weekly Progression
- Each week, your instructor releases a new chapter
- Complete challenges before the solution is released
- Solutions come out when the next chapter is released

---

## For Instructors (Managing the Course)

### Initial Setup

```bash
# Clone the repository
git clone <your-repo-url>
cd learn-python

# You're on main branch (overview only)
# Students see: README.md, QUICKSTART.md
```

### Weekly Release Schedule

#### Week 1: Release Chapter 1
```bash
# Create chapter 1 branch for students
git checkout -b chapter-01-beginning
git add notebooks/chapter_01_beginning.ipynb
git commit -m "Release Chapter 1: The Beginning"
git push origin chapter-01-beginning
```

**Students work on Chapter 1 this week.**

#### Week 2: Release Chapter 1 Solution + Chapter 2
```bash
# Create solution branch
git checkout -b chapter-01-solution
# Add solution code to the notebook (fill in all challenges)
# Edit chapter_01_beginning.ipynb with solutions
git add notebooks/chapter_01_beginning.ipynb
git commit -m "Chapter 1: Complete solution"
git push origin chapter-01-solution

# Release Chapter 2
git checkout -b chapter-02-control-flow
git add notebooks/chapter_02_control_flow.ipynb
git commit -m "Release Chapter 2: Control Flow"
git push origin chapter-02-control-flow
```

**Students can now:**
- Review Chapter 1 solution on `chapter-01-solution` branch
- Start Chapter 2 on `chapter-02-control-flow` branch

#### Week 3: Continue the pattern
```bash
# Solution for Chapter 2
git checkout -b chapter-02-solution
# ... add solutions ...

# Release Chapter 3
git checkout -b chapter-03-loops
git add notebooks/chapter_03_loops.ipynb
git commit -m "Release Chapter 3: Loops"
git push origin chapter-03-loops
```

### Branch Structure

```
main (overview only)
├── chapter-01-beginning (student work)
├── chapter-01-solution (released week 2)
├── chapter-02-control-flow (student work)
├── chapter-02-solution (released week 3)
├── chapter-03-loops (student work)
├── chapter-03-solution (released week 4)
└── ... continue pattern
```

### Creating Solution Branches

To create a solution branch:
1. Checkout the student branch
2. Create new branch: `git checkout -b chapter-XX-solution`
3. Edit the notebook and fill in all challenge solutions
4. Add explanation comments
5. Test that all code runs correctly
6. Commit and push

Example solution code:
```python
# 🎯 CHALLENGE 1: Create Your Character
# ═══════════════════════════════════════════════════════════════

# 👇 SOLUTION 👇
player_name = "Aragorn"  # Can be any name
player_health = 100       # Must be 100
player_gold = 50         # Must be 50
player_level = 1         # Must be 1

# 💡 EXPLANATION:
# We create four variables to store player information.
# Notice that strings need quotes, but numbers don't!
```

### Distribution Methods

**Option 1: GitHub** (Recommended)
- Students clone/download from GitHub
- Easy version control
- Clear branch structure

**Option 2: Google Drive**
- Upload notebooks to shared Google Drive folder
- Students make copies to their own Drive
- Name folders by week: "Week 1 - Chapter 1", etc.

**Option 3: Canvas/LMS**
- Upload notebooks as assignments
- Students download and upload to Colab
- Attach solutions as feedback after deadline

### Tips for Teaching

1. **Do a live demo** in Week 1 showing how to:
   - Access Google Colab
   - Upload a notebook
   - Run cells
   - Complete a challenge
   - Run tests

2. **Set deadlines:**
   - Chapter due Friday
   - Solution released Monday
   - New chapter released Monday

3. **Office hours:**
   - Review failed tests together
   - Debug code as a group
   - Live coding sessions

4. **Encourage collaboration:**
   - Students can help each other understand concepts
   - But each student writes their own code
   - Copying is not learning!

5. **Track progress:**
   - Check who completes each chapter
   - Offer extra help to students falling behind
   - Celebrate milestones!

---

## Testing Notebooks

Before releasing, test each notebook:

```bash
# Install Jupyter locally
pip install jupyter notebook

# Open the notebook
jupyter notebook notebooks/chapter_01_beginning.ipynb

# Test:
# 1. Run all cells in order
# 2. Complete all challenges
# 3. Verify tests pass
# 4. Check for typos/errors
```

---

## Customization Ideas

- **Adjust difficulty:** Modify challenge requirements
- **Add bonus challenges:** For advanced students
- **Change the theme:** Sci-fi instead of fantasy
- **Add robot examples:** Connect concepts to robotics
- **Create leaderboards:** Track fastest completion times
- **Add achievements:** Digital badges for milestones

---

## Need Help?

- **GitHub Issues:** Report bugs or ask questions
- **Discussions:** Share teaching strategies
- **Pull Requests:** Contribute improvements

---

## License

This curriculum is open source and free for educational use. Modify it to fit your students' needs!

**Happy Teaching! 🎓**
