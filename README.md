# 2023-09-11-git_history Lecture3

- 'add <FILENAMES>': adding the (filename) to the staging area
- 'commit -m"messaege"': commit witha  message everyhing in the stagin area
- 'push <WHERE> <WHAT>': pushes the history.commits to the remote (where ) using the commits from the specified branch (what)
- 'pull <WHERE> <wHAT>': pulls (updates) the local repo with conents in the remote (where) using the information in the specified branch (what)

- 'log': shows the log
    - 'log --oneline': shows the log in condenced format
    - this may open ua terminal program called 'less' that lets you scroll.
        - use 'q' to quit out of less

- 'diff': shows you the "difference" between your changes and the last known git state
    - 'diff --staged': shows you the diff of the fiels in the staging area

- 'restore --staged <FILENAME>': unstages
