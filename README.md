# 🧠 My-EDAs

This repository contains my Exploratory Data Analysis (EDA) projects, each organized into its own folder. Every folder includes the dataset, analysis scripts, and visuals related to a specific dataset.

---

## 📁 Folder Structure

```text 
My-EDAs/
├── Basic EDA of Hepatitis Dataset/
│ ├── hepatitis.csv
│ └── eda.ipynb
├── README.md
└── (More folders coming soon...)
```

Each folder is:

- Fully self-contained  
- Focused on one dataset  
- Easy to browse, understand, and build upon  

---

## 🚀 Git Setup Info

### 🔹 Where Git is Initialized

Git is initialized at the **top-level folder**: `My-EDAs/`.

That means:

- All subfolders (like `Basic EDA of Hepatitis Dataset/`) are part of **one single Git repo**
- You should **not** run `git init` inside the subfolders

---

### 🔹 Notes for Collaborators

This is a **monorepo-style setup**, where multiple EDA projects live inside one Git repository.

If you want to work on **just one subfolder**, here are your options:

---

#### ✅ Option 1: Clone the whole repo and work on your part

```text 
git clone https://github.com/PheonixLione/My-EDAs.git
```

Then:

- Go into the folder you want to work on
- Make your changes
- Commit the changes
- Push to your fork or branch

---

#### ✅ Option 2: Copy just the folder and make a new repo

If you only want a specific subfolder (like `Basic EDA of Hepatitis Dataset/`) and don’t care about the rest of the repo:

- Copy that folder to your system
- Initialize a new Git repo inside it:

```text
git init
git add .
git commit -m "Initial commit"
git remote add origin <your-new-repo-url>
git push -u origin main
```

> ⚠️ This will create a new standalone GitHub repo for that folder, separate from this one.

---

## 🙌 Contributions

If you’d like to add your own EDA on a dataset:

1. 🔀 Fork this repo
2. 📁 Create a new folder with a clear and descriptive name
3. 📂 Add your code, dataset, and outputs
4. 🚀 Open a Pull Request

---

## 📬 Contact

Got questions or suggestions?

- Open an Issue
- Or submit a Pull Request

Let’s make data exploration easier together!

---

