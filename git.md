- Initialize a git repository

  - This is the first thing you want to do when making a git repo. You will not have to do this ever again for that folder.

  ```
  $ git init
  ```

- Saving your changes
  - First add what files you want to save. Most common thing to do is add all the file in the folder, but you are welcome to just add an individual file if you want.
  - Add all files
  ```
  $ git add .
  ```
  -add a single file
  ```
  $ git add filename.extension
  ```
  - Second you need to commit those changes.
  ```
  $ git commit -m "Your commit message"
  ```
- If you ever get lose run the following command. This will help you understand the git repo.
  ```
  $ git status
  ```

# Github

- First create a repo on github. Try and name it the same as your local git repo.
- Copy the 3 lines for existing repos
- Paste into the terminal
  - Make sure your in the correct directory
- Whenever you need to push new changes to github do the following:

```
$ git push
```
