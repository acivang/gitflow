### 1. Make an existing Git branch track a remote branch?

* Given a branch foo and a remote upstream:

  **As of Git 1.8.0:**
  
  ```
  git branch -u upstream/foo
  ```

  * Or, if local branch foo is not the current branch:

  ```
  git branch -u upstream/foo foo
  ```

  * Or, if you like to type longer commands, these are equivalent to the above two:

  ```
  git branch --set-upstream-to=upstream/foo // set current branch tracking remote branch

  git branch --set-upstream-to=upstream/foo foo // set the branch of foo tracking remote branch
  ```

  **As of Git 1.7.0:**
  ```
  git branch --set-upstream foo upstream/foo
  ```

  > **参考资料：**</br>
  > [Make an existing Git branch track a remote branch?](https://stackoverflow.com/questions/520650/make-an-existing-git-branch-track-a-remote-branch) </br>
  > [checkout tracked remote branch](http://gitready.com/intermediate/2009/01/09/checkout-remote-tracked-branch.html)</br>
  > [Adding a tracking branch](https://githowto.com/adding_a_tracking_branch)

### 2. 
