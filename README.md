# DSCI 521: Lecture 3

- `add <FILENAMES>`: adding the <FILENAMES> to the staging area
- `commit -m "MESSAGE"`: commit with a message everything in the staging area
- `push <WHERE> <WHAT>`: pushes the history/commits to the remote (where) using the commits from the specified branch (what)
- `pull <WHERE> <WHAT>`: pulls (updates) the local repo with conents in the remote (where) using the information in the specified branch (what)

- `log`: shows the log
    - `log --oneline`: shows the log in condenced format
    - this may open a terminal program called `less` that lets you scroll.
      - use `q` to quit out of less

- `diff`: shows you the "difference" between your changes and the last known git state
  - `diff --staged`: shows you the diff of the files in the staging area

- `restore --staged <FILE>`: unstages <FILE> from the staging area

- `revert <SHA1>`: undos the changes in the commit specified in `<SHA1>`