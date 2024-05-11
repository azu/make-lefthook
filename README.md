# Lefthook modify .githooks

## Usage

    git clone https://github.com/azu/make-lefthook
    make setup
    
    touch index.js
    git add .
    git commit -m "Add index.js"
    
    # lefthook modify .githooks/pre-commit file
    git status
    On branch main
    Your branch is ahead of 'origin/main' by 1 commit.
    (use "git push" to publish your local commits)

    Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git restore <file>..." to discard changes in working directory)
        modified:   .githooks/pre-commit
        modified:   .githooks/prepare-commit-msg
