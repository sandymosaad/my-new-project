## .1 Removing Branches Locally and Remotely

### Removing Branches Locally
To remove a branch locally, we can use the `git branch -d` command or `git branch -D` if the branch is not yet merged.

# Remove a branch locally
git branch -d dev
git branch -d test

# Remove a branch remotely
git push origin --delete dev
git push origin --delete test

## .2 Checkout Another Branch Without Committing Changes

### Using Git Stash

# Stash your changes
git stash

# Checkout another branch
git checkout <branch-name>

# Apply your stashed changes
git stash apply

## 3. Listing Tags

To list all tags in our Git repository, we use the following command in our terminal: git tag

## 4. Deleting Tags

### Deleting a Tag Locally

To delete a tag locally in Git, use the following command:
git tag -d <tag-name>

### Deleting a Tag remotely
git push origin --delete <tag-name>



## 5. Add an image 

![Project Logo](IMG/IMG_20231029_164158.jpg)



