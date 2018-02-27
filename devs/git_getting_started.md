# Getting Started

Generate SSH Keys

1. ssh-keygen -t rsa -C "your.email@example.com" -b 4096
2. Copy the .pub to your github account
3. Clone the repo

# Clone Repo
1. Configure git global.
2. Clone repos.
3. Create branch for changes.
    ```
    git checkout -b <branch-name>
    ```
4. Commit the changes and push the local branch.
    ```
    git add .
    git commit .
    git push origin <branch-name>
    ```
5. Create Merge Request once tasks is complete.
