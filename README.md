# 🐍 Quest for the Python Crown
## An Interactive Python Learning Adventure for Robotics Club

Welcome, brave adventurer! You're about to embark on an epic journey to learn Python programming through building a text-based adventure game. By the end of this course, you'll have the skills to program your robots AND a complete game you built yourself!

---

## 🎮 What You'll Build

Throughout this course, you'll build **Quest for the Python Crown** - a complete CLI (Command Line Interface) adventure game where players:
- Create and customize their hero
- Make choices that affect the story
- Battle enemies in turn-based combat
- Collect items and manage inventory
- Explore a fantasy world
- Save and load their progress

But more importantly, you'll learn **professional Python programming skills** that will help you with robotics, automation, and software development!

---

## 📚 Course Structure

This course is organized into **chapters**, with each chapter teaching new Python concepts through game development. Each chapter is a separate **git branch** that you'll work through one at a time.

### **PART I: FOUNDATIONS (Chapters 1-5)**
*Building the Core Game Engine*

#### **Chapter 1: The Beginning - Your First Adventure**
- Variables and data types (strings, integers, floats)
- Print statements and f-strings
- User input with `input()`
- Comments and documentation
- **Game Feature:** Welcome system and player name input

#### **Chapter 2: Choosing Your Path - Control Flow**
- Boolean values and comparison operators
- `if`/`elif`/`else` statements
- Nested conditionals
- Logical operators (`and`, `or`, `not`)
- **Game Feature:** Story branching and decision-making

#### **Chapter 3: The Journey Continues - Loops**
- `while` loops and `for` loops
- `range()` function
- `break` and `continue` statements
- Loop control flow
- **Game Feature:** Game loop and room exploration

#### **Chapter 4: Your Inventory - Lists and Collections**
- Lists: creation, indexing, slicing
- List methods (`append`, `remove`, `pop`, `insert`)
- Tuples and immutability
- List comprehensions (basic)
- **Game Feature:** Inventory system

#### **Chapter 5: Character Stats - Dictionaries**
- Dictionary creation and access
- Dictionary methods (`get`, `keys`, `values`, `items`)
- Nested dictionaries
- **Game Feature:** Player stats and item properties

### **PART II: STRUCTURING CODE (Chapters 6-10)**
*Building Reusable Systems*

#### **Chapter 6: Your Arsenal - Functions**
- Function definition and calling
- Parameters and return values
- Scope (local vs global)
- Docstrings
- **Game Feature:** Combat calculation functions

#### **Chapter 7: Advanced Tactics - More Functions**
- `*args` and `**kwargs`
- Lambda functions
- Higher-order functions
- Recursion basics
- **Game Feature:** Dynamic ability system

#### **Chapter 8: Saving Your Progress - File I/O**
- Reading and writing text files
- JSON serialization
- Context managers (`with` statement)
- Error handling for files
- **Game Feature:** Save/load game functionality

#### **Chapter 9: Handling Disaster - Exception Handling**
- `try`/`except` blocks
- Multiple exception types
- Raising exceptions
- Custom exceptions
- **Game Feature:** Graceful error recovery

#### **Chapter 10: Testing Your Skills - Unit Testing**
- pytest basics
- Writing test cases
- Assertions and coverage
- Test-driven development
- **Game Feature:** Comprehensive test suite

### **PART III: OBJECT-ORIENTED ADVENTURE (Chapters 11-15)**
*Building Professional Game Architecture*

#### **Chapter 11: Creating Heroes - Classes and Objects**
- Class definition and instantiation
- `__init__` constructor
- Instance attributes and methods
- **Game Feature:** Player and Enemy classes

#### **Chapter 12: Legendary Creatures - Inheritance**
- Inheritance basics
- `super()` function
- Method overriding
- Polymorphism
- **Game Feature:** Specialized enemy types

#### **Chapter 13: Special Powers - Magic Methods**
- Comparison methods (`__eq__`, `__lt__`, etc.)
- Arithmetic methods (`__add__`, `__sub__`)
- Sequence methods (`__len__`, `__getitem__`)
- **Game Feature:** Equipment comparison system

#### **Chapter 14: Powerful Enchantments - Advanced OOP**
- Properties (`@property` decorator)
- Class methods and static methods
- Multiple inheritance and mixins
- **Game Feature:** Calculated stats and skill system

#### **Chapter 15: The Game Master - Design Patterns**
- Singleton pattern
- Factory pattern
- Observer pattern
- Strategy pattern
- **Game Feature:** Global game manager and AI system

### **PART IV: ADVANCED TECHNIQUES (Chapters 16-20)**
*Polishing Your Masterpiece*

#### **Chapters 16-20:** Advanced topics including comprehensions, decorators, modules, external libraries, and best practices

---

## 🚀 Getting Started

### **For Chromebook Users (Recommended)**

Since you're using Chromebooks in robotics club, we'll use **Google Colab** - a free, cloud-based Jupyter notebook environment that runs entirely in your browser!

#### **Step 1: Set Up Google Colab**

1. Open your web browser and go to [Google Colab](https://colab.research.google.com/)
2. Sign in with your Google account (use your school account if available)
3. You'll see the Colab welcome page - you're ready to go!

#### **Step 2: Get the Course Materials**

**Option A: Download from GitHub (Recommended)**
1. Go to the course repository: `https://github.com/YOUR-USERNAME/python-quest`
2. Click the green "Code" button → "Download ZIP"
3. Extract the ZIP file
4. Upload the notebook to Google Drive
5. Right-click the `.ipynb` file → "Open with" → "Google Colaboratory"

**Option B: Clone with Git (Advanced)**
```bash
# In a Colab notebook cell:
!git clone https://github.com/YOUR-USERNAME/python-quest.git
%cd python-quest
!git checkout chapter-01-beginning
```

#### **Step 3: Start Chapter 1**

1. Open `chapter_01_beginning.ipynb` in Google Colab
2. Read the instructions carefully
3. Run each cell by clicking the "Play" button or pressing `Shift + Enter`
4. Complete the challenges
5. Run the test cells to check your work!

### **For Windows/Mac/Linux Users**

If you're working on a laptop or desktop:

#### **Step 1: Install Python**

1. Download Python 3.10+ from [python.org](https://www.python.org/downloads/)
2. During installation, check "Add Python to PATH"
3. Open Terminal/Command Prompt and verify: `python --version`

#### **Step 2: Install Jupyter**

```bash
pip install jupyter notebook
```

#### **Step 3: Clone the Repository**

```bash
git clone https://github.com/YOUR-USERNAME/python-quest.git
cd python-quest
git checkout chapter-01-beginning
```

#### **Step 4: Launch Jupyter**

```bash
jupyter notebook
```

This will open Jupyter in your browser. Navigate to `chapter_01_beginning.ipynb` and start learning!

---

## 📖 How to Use This Course

### **Weekly Release Schedule**

Each week, your instructor will release a new chapter:

1. **Week 1:** Chapter 1 released (branch: `chapter-01-beginning`)
2. You work on challenges during the week
3. **Week 2:** Chapter 1 solution released (branch: `chapter-01-solution`) + Chapter 2 released (branch: `chapter-02-control-flow`)
4. Review the solution, ask questions, then start Chapter 2
5. Repeat!

### **Working Through a Chapter**

Each chapter follows this structure:

1. **📖 Theory Sections**: Learn new Python concepts with clear explanations
2. **🎯 Interactive Examples**: See the concepts in action - run the code and experiment!
3. **🎮 Game Examples**: See how these concepts build the game
4. **💻 Challenges**: Your turn! Write code to solve problems
5. **✅ Tests**: Run automated tests to check your solutions
6. **🏆 Bonus Challenges**: Extra credit for advanced students

### **Tips for Success**

✅ **Read everything carefully** - Don't skip the theory sections!
✅ **Run every code cell** - Even the examples. See what happens!
✅ **Experiment freely** - Change values, break things, learn by doing
✅ **Test often** - Run the test cells to check your progress
✅ **Ask questions** - In robotics club meetings or on Discord
✅ **Help each other** - Collaborate, but don't copy!
✅ **Have fun** - You're building a game while learning to code!

### **When You Get Stuck**

1. **Read the error message** - Python tells you what's wrong!
2. **Check the examples** - Look at the working code above the challenge
3. **Review the theory** - Re-read the explanation section
4. **Test incrementally** - Don't write everything at once, test as you go
5. **Ask for help** - That's what robotics club is for!

---

## 🧪 Running Tests

Each chapter includes automated tests to verify your solutions. Here's how to read test results:

```
✅ PASS: Variable 'player_name' exists with correct type
✅ PASS: player_health equals 100
❌ FAIL: player_gold equals 50
   Reason: Expected 50, got 0

═══════════════════════════════════════════════════════════════
RESULTS: 2/3 tests passed
═══════════════════════════════════════════════════════════════
```

- ✅ = Test passed! You got it right!
- ❌ = Test failed. Read the reason and fix your code.

### **Test-Driven Learning**

Tests are your friend! They:
- Tell you exactly what's expected
- Give immediate feedback
- Help you learn to debug
- Build good programming habits

Don't just try to "pass the tests" - **understand why** your solution works!

---

## 💾 Saving Your Work

### **In Google Colab:**

1. Colab auto-saves to your Google Drive
2. File → "Save a copy in Drive" to make a backup
3. Download: File → "Download" → "Download .ipynb" for local backup

### **In Jupyter Notebook:**

1. Click the "Save" icon or press `Ctrl+S` / `Cmd+S`
2. Files are saved to your local computer
3. Use git to track your progress:

```bash
git add .
git commit -m "Complete Chapter 1"
git push
```

---

## 🎯 Learning Objectives

By the end of this course, you will be able to:

- ✅ Write clean, well-structured Python code
- ✅ Understand fundamental programming concepts
- ✅ Use object-oriented programming (OOP)
- ✅ Handle errors gracefully
- ✅ Write and run automated tests
- ✅ Work with files and data
- ✅ Build interactive command-line applications
- ✅ Apply these skills to robotics programming!

---

## 🤖 Connection to Robotics

The skills you learn in this course directly apply to robotics:

| Python Concept | Robotics Application |
|----------------|---------------------|
| Variables & Data Types | Storing sensor readings, robot state |
| Control Flow | Making decisions based on sensor input |
| Loops | Continuous robot operation, scanning |
| Lists | Storing waypoints, sensor histories |
| Dictionaries | Robot configuration, sensor mappings |
| Functions | Reusable robot behaviors |
| Classes | Robot controllers, sensor objects |
| Error Handling | Dealing with sensor failures |
| File I/O | Saving mission data, loading configs |

---

## 🏆 Completion Certificate

When you complete all chapters and your final game runs successfully, you'll receive:

- ✅ A completion certificate for your portfolio
- ✅ A complete, working game you built yourself
- ✅ Skills to contribute to robotics club projects
- ✅ A GitHub repository to show future employers/colleges

---

## 📞 Getting Help

- **During Robotics Club:** Ask your instructor or peers
- **Discord:** [Link to your club Discord]
- **GitHub Issues:** Report bugs or ask questions
- **Office Hours:** [Your availability]

---

## 🎮 Ready to Begin?

1. Make sure you can access Google Colab: [colab.research.google.com](https://colab.research.google.com)
2. Test that you can run a code cell (try: `print("Hello, Python!")`)
3. Check out the first chapter: `git checkout chapter-01-beginning`
4. Open `chapter_01_beginning.ipynb`
5. **Begin your quest!**

---

## 📜 License

This course is open source and free to use for educational purposes.

---

**Now, let's start your journey to become a Python Master!** 🐍👑

*May your code be bug-free and your adventures legendary!*
