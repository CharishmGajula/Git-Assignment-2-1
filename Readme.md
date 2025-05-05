# initializing a repository
--> git init


# creating a readme.md file

# creating a file
--> read.txt

# add some data to it 
Minfy tech solutions
I am Charishma
from Telangana
Learning new things
My roll number is 1234
About to learn.


# know the status
 --> git status

git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        read.txt

nothing added to commit but untracked files present (use "git add" to track)

# Add it to staging
--> git add .

# commit it 
git commit -m "initial commit"

[master (root-commit) 86380f5] initial commit
 1 file changed, 6 insertions(+)
 create mode 100644 read.txt

# making the changes
----> # Changed the name into full name --> modified a line

    --> git status
    --> git add .
    --> git commit -m "changed the name to full name"

----> # added another line

    --> git status
    --> git add .
    --> git commit -m "Added another line"

---> # Changed the roll number --> modified a line
    
    --> git status
    --> git add .
    --> git commit -m "changed the roll number"


# getting the log of commits

git log

commit 1613d3ef3702c46c185a94f52e9a74b3c9705ea7 (HEAD -> master)
Author: CharishmaGajula <charishma.gajula@minfytech.com>
Date:   Mon May 5 13:56:15 2025 +0530

    changed the roll number

commit 83c48feb03d796092e32ce38a9332e0aff648348
Author: CharishmaGajula <charishma.gajula@minfytech.com>
Date:   Mon May 5 13:55:37 2025 +0530

    added another new line

commit f5e1272c920f7305ce7b65b0631c69f4c8bdd4fb
Author: CharishmaGajula <charishma.gajula@minfytech.com>
Date:   Mon May 5 13:53:58 2025 +0530

    changed the name into full name

commit 86380f5a30de5a50c4210949e8830d995276bef2
Author: CharishmaGajula <charishma.gajula@minfytech.com>
Date:   Mon May 5 13:50:54 2025 +0530

    initial commit

<img width="960" alt="assignment 1" src="https://github.com/user-attachments/assets/1de1fafe-ce6d-47bc-821d-5b00fef0b245" />


# getting the difference of the lines from one commit to other

git diff 86380f5a30de5a50c4210949e8830d995276bef2 f5e1272c920f7305ce7b65b0631c69f4c8bdd4fb
diff --git a/read.txt b/read.txt
index 2fd49fc..134a765 100644
--- a/read.txt
+++ b/read.txt
@@ -1,5 +1,5 @@
 Minfy tech solutions
-I am Charishma
+I am Charishma Gajula
 from Telangana
 Learning new things
 My roll number is 1234


PS C:\Users\Minfy.GOPITHOTA\Desktop\git> git diff f5e1272c920f7305ce7b65b0631c69f4c8bdd4fb 1613d3ef3702c46c185a94f52e9a74b3c9705ea7
diff --git a/read.txt b/read.txt
index 134a765..293ab87 100644
--- a/read.txt
+++ b/read.txt
@@ -2,5 +2,6 @@ Minfy tech solutions
 I am Charishma Gajula
 from Telangana
 Learning new things
-My roll number is 1234
-About to learn.
\ No newline at end of file
+My roll number is 12e4
+About to learn.
 My roll number is 1234


 <img width="960" alt="assignment 1 git diff" src="https://github.com/user-attachments/assets/b425d7c8-5112-4209-a565-674d024c9403" />



# pushing the repository into github

git push -u origin master



# created another branch feature1
 git checkout -b feature1


# pull request succesfull
<img width="934" alt="image" src="https://github.com/user-attachments/assets/598805b3-bd60-4f28-998a-e14e48ab4c91" />

 
