# I'm making fun codestuff! sweet
awesome!


## Git commands
Untracked --> Unstaged --> Staged --> Committed --> Pushed

* add SSH url - only have to do this once to set up
    ```sh
    git remote add origin <Github ssh url>
    ```
* what is happening?
    ```sh
    git status
    ```
* Untracked to unstaged
    ```sh
    git add -N .
    git add -N folder
    git add -N filename.txt
    ```

* Unstaged to staged
    ```sh
    git add -p # (p refers to "patches" of code) Y/N/Q
    ```

* Staged to committed
    ```sh
    git commit -m "Add a description" # (m refers to "message")
    ```

* Committed to pushed
    ```sh
    git push origin master # origin is where, master is what
    ```
