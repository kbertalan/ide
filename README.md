# ide

Small tmux script to quickly start up a 3 pane window in tmux for development.

The panes started are:

- editor, by default nvim (EDITOR env variable)
- countinous build/test/run, relies on a project specific dev.sh (BUILDER env variable)
- git

