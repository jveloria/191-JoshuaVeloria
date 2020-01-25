(1) What does git log look like?
commit fd05eb70c7a488f1f1a71f2b7ff2794af08c4959 (HEAD -> master)
Author: jveloria <jveloria@uci.edu>
Date:   Fri Jan 24 19:37:00 2020 -0800

    commit for commit tutorial

commit 2cdb8f4e5685eae382905c07338b55c2d3cec18b (origin/master, greeting)
Author: jveloria <jveloria@uci.edu>
Date:   Fri Jan 24 18:50:48 2020 -0800

    committed2

commit cd3b5cc5add1082b52c4163a3d4444a827cb08ae
Author: jveloria <jveloria@uci.edu>
Date:   Fri Jan 24 18:47:12 2020 -0800

    committed

commit cf80b6fe43a20498942379dfbbfa23eae8d2c6f4 (greeting.txt)
Author: jveloria <jveloria@uci.edu>
Date:   Fri Jan 24 18:21:02 2020 -0800

     Initial commit

(2)What does the output from git status look like now?
On branch master
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    newfile.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .project
        testfile.txt

no changes added to commit (use "git add" and/or "git commit -a")

(3)How does git status look now?
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   testfile.txt

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    newfile.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .project

(3)How does git status look now?
On branch master
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    newfile.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .project

no changes added to commit (use "git add" and/or "git commit -a")

(4)What does git status look like now?
On branch master
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    newfile.txt
        modified:   testfile.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .project

no changes added to commit (use "git add" and/or "git commit -a")

(5)What does git status look like now?
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   testfile.txt

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    newfile.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .project

(6)What does the status look like now? The log?
- STATUS LOOKS LIKE:
On branch master
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    newfile.txt
        modified:   testfile.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .project

no changes added to commit (use "git add" and/or "git commit -a")

- LOG LOOKS LIKE: 
Author: jveloria <jveloria@uci.edu>
Date:   Fri Jan 24 19:45:18 2020 -0800

    commit #2 for tutorial (2nd attempt)

commit 2e1d08d01a1deb4b25be0cba393627a0c5260394
Author: jveloria <jveloria@uci.edu>
Date:   Fri Jan 24 19:43:08 2020 -0800

    for the commit tutorial (2nd attempt)

commit fd05eb70c7a488f1f1a71f2b7ff2794af08c4959
Author: jveloria <jveloria@uci.edu>
Date:   Fri Jan 24 19:37:00 2020 -0800

    commit for commit tutorial

commit 2cdb8f4e5685eae382905c07338b55c2d3cec18b (origin/master, greeting)
Author: jveloria <jveloria@uci.edu>
Date:   Fri Jan 24 18:50:48 2020 -0800

    committed2

commit cd3b5cc5add1082b52c4163a3d4444a827cb08ae
Author: jveloria <jveloria@uci.edu>
Date:   Fri Jan 24 18:47:12 2020 -0800

    committed

commit cf80b6fe43a20498942379dfbbfa23eae8d2c6f4 (greeting.txt)
Author: jveloria <jveloria@uci.edu>
Date:   Fri Jan 24 18:21:02 2020 -0800

     Initial commit
(END)

