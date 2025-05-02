# **📘 Day-18: Managing Exercises Using GitHub**

Welcome to **Day-18** of our Java backend journey! Today, we stepped away from coding just a bit to strengthen one of the most **crucial developer habits**: using **GitHub effectively to manage your exercises and projects**. If code is the brain of your app, Git is its memory – don’t trust your future self to remember `final-final2-really-done-this-time.java` 😅.

---

## **📌 Lesson Structure**

### **1️⃣ Git & GitHub Refresher**

* **Git** is a local version control system.
* **GitHub** is a remote platform to host, share, and collaborate on repositories.

#### 🧠 Core Git Concepts:

* Repository (`repo`)
* Commit
* Branch
* Push / Pull
* Merge
* `.gitignore`

---

## **🗂️ Organizing Your Exercises**

### ✅ One Repo, Many Folders Approach

```plaintext
java-exercises/
├── Day-01_Basics/
│   └── HelloWorld.java
├── Day-02_ControlFlow/
│   └── IfElseExample.java
├── Day-03_Collections/
│   └── ArrayListDemo.java
...
```

> 📁 Keep each day self-contained with meaningful naming.

---

## **🔧 Git Workflow for Daily Exercises**

### **🔹 Step-by-Step Git Flow**

```bash
# Initialize a repo (only once)
git init

# Track a new file
git add Day-18_GitHub_Exercises/README.md

# Save a snapshot
git commit -m "Day-18: Added GitHub exercise management guide"

# Connect to GitHub (only once)
git remote add origin https://github.com/your-username/java-exercises.git

# Push your code
git push -u origin main
```

> 🎯 Commit early, commit often. Small, descriptive commits are best!

---

## **📁 Recommended Structure for README in Each Day Folder**

```
# 📘 Day-XX: [Topic Title]

## ✅ Goals
- Bullet points of what was learned.

## 💻 Code Samples
- List or link key Java files in the folder.

## 🧪 Output Examples
- Screenshot or text of expected output.

## 📚 Notes
- Any important learning points.
```

---

## **🔄 Collaborating & Pull Requests (Optional Preview)**

* Clone → Change → Push → Create Pull Request.
* Useful if you're working in teams or reviewing each other's code.

> Don’t worry, we’ll dive into real pull requests and code reviews in a future lesson!

---

## **📦 Using `.gitignore`**

Create a `.gitignore` to keep your repo clean:

```gitignore
*.class
*.log
.idea/
target/
```

> Keeps junk and build files out of version control.

---

## **🧠 Pro Tips**

* Use **descriptive commit messages**.
* Keep your GitHub repo **public** to showcase your growth.
* Use **Markdown** in READMEs for documentation practice.
* Avoid pushing secrets like API keys. (GitHub will scream at you now, thankfully!)

---

## **🎯 Exercises**

✅ Create a new GitHub repo and push at least 3 days' worth of code.
✅ Add a `.gitignore` file tailored to Java.
✅ Add a README for each day.
✅ Try creating a branch and merging it back to `main`.

---

## **📚 Additional Resources**

* [GitHub Docs: Getting Started](https://docs.github.com/en/get-started)
* [Gitignore for Java Projects](https://github.com/github/gitignore/blob/main/Java.gitignore)
* [Git Handbook by GitHub](https://guides.github.com/introduction/git-handbook/)

---

## **🎥 Video Lesson Recording**

📺 [Video Lesson Recording](https://us06web.zoom.us/rec/share/iv1eSEQz22hK_BRiMAvo2eW2ZQ2QC34XyCt9ethefyGOFWaVmzihZFruXzlUEeiE.MeXvnJpx4nPuyRQc?startTime=1744183400000)*

---

🚀 **Great job today! Now your code has a home, a history, and some swagger. See you tomorrow – and may your commits be clean and your merge conflicts rare!** 😄


