# Git & GitHub Terminal Lab

Welcome! The goal of today's session is to master the **Git Terminal** workflow. You will add your name to the participants list by interacting with this repository.

## Step-by-Step Terminal Guide

### 1. Fork this Project
First, click the **"Fork"** button at the top right of this GitHub page to create your own copy.

### 2. Clone your Fork
Open your terminal and run these commands (replace `YOUR_USERNAME` with your real GitHub name):

git clone https://github.com/YOUR_USERNAME/git-java-lab.git
cd git-java-lab

### 3. Create a Working Branch
Create a new branch for your contribution, replace your-name with your real name and surname (e.g., mikel-idoyaga)

git checkout -b your-name

### 4. Edit the File
Open `Participants.java` with any text editor and add your line inside the `main` method:
greet("Your Name", "your-github-username");

### 5. Stage and Commit Changes
You must first "add" the file to the staging area and then "commit" it:

git add Participants.java
git commit -m "Add [Your Name] to the list"

### 6. Push to GitHub
Upload your branch to your GitHub profile:

git push origin your-name

### 7. Open the Pull Request (PR)
Go to the original repository on GitHub, click the green **"Compare & pull request"** button and submit it.

---
*Note: Wait for the ✅ or ❌ icon in your PR to see if your Java code is correct.*
