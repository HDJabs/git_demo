step one: add this project to the git repo
    git init
    git add *
    git commit
    $ git remote add origin https://github.com/HDJabs/git_demo
    $ git push -u origin master

step 2: checkout the master branch
    git checkout -b master

step 3: add the STEPS.md file
    git add STEPS.md
    git commit -m "added the STEPS.md file"

step 4: update and commit the STEPS.md (what im about to do right now)
    git add STEPS.md
    git commit -m "step 4. pdate the STEPS.md file"
    git push

step 5: checkout main branch, and update README
    git checkout main
    (update README)
    git add README.md
    git commit -m "step 5. updated the README"
    git push

step 6: merge the two branches
    git checkout master
    git add STEPS.md
    git commit "step 6. updating steps, and about to merge"
    git merge main