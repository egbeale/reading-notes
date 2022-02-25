# Revisions and the Cloud

## TERMINAL COMMANDS

>CLONE
>
> - git clone codeURL
> - code .

> ACP
>
> - git add README.md
>   - git add code .
> - git commit -m "add message"
> - git push origin main

> See changes
>
> - git status

> Delete file
>
> - rm fileName

---

# Sharing Code

## GITHUB

- A way to share code with others. stores code in the cloud (free up your computer)
- Separate from Git, but uses git to help you manage work

### REPOSITORIES

- Collection of files that Git will watch over for you
- Can be remote (lives on GitHub) or local (lives on your computer)

CREATE REPO

- Make public, Add README file
- Then to Settings >> Pages > Branch: main

DEPLOY IT

- Settings >> pages >> copy code
- Code >> cog (edit) >> paste code

## CLONING

Links cloud repo with local repo

- In GitHub repo - CODE button - copy URL
- In TERMINAL: Go to the correct folder in directory

  - **git clone URL**
  - **code .** ("code" space dot - opens it vs code)

See the URL of gethub repo by typing: git remote -v

## ACP: Add . Commit . Push

After editing repo in VS code...

**git status** - Tells you what files have changed since last commit

### **ADD**

- git add fileName
- git add README.md
- Tells git to include these changes in the next snapshot

### **COMMIT**

- git commit -m "specify edit here"

### **PUSH.**

- git push origin main
  - main = branch name
