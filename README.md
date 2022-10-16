# note-app
(Take Your Note) Store all notes and important information digitally, usually in a cloud-based storage system.  App is build up with React js

## Good Practices

1. Before doing fetching any records from upstream or pushing, always check if
   you are in the right branch. You can see what branch you are in by running
   the following command: `git branch`

2. Before doing any new work, always run `git fetch upstream` and then
   `git merge upstream/master` on the master branch. If you are not in the
   master branch, simply run `get checkout master` first to make sure you are in
   the master branch.

3. Keep every commit and its message meaningful and relevant.

4. Keep your PR titles meaningful and relevant.

5. Always include `ifix-` before your branch names. That’s our common pattern.
   `i` there is issue and fix is the fix you are providing.
