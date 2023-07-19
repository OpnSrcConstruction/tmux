# tmux
my custom tmuxrc config dir. and config-file.


Some of my favorite features:
* tm-pin ctrl sensible move bindings
    * splitting panes:
        - prefix + | = split current pane horizontally.
        - prefix + \ = split full width horizontally.
        - prefix + - = split pane vertically.
        - prefix + + = split pane Fully vertically.
    * Navigating panes:
        - prefix + h = navigate left
        - prefix + j = navigate down
        - prefix + k = navigate up
        - prefix + l = navigate right
    * Resizing panes:
        - prefix + H = resize current selected pane 5 col.s left
        - prefix + J = resize current selected pane 5 rows down
        - prefix + K = resize current selected pane 5 rows up
        - prefix + L = resize current selected pane 5 col.s right
* tmux-plugins/open
   - Searches DDG/ = ctrl + shift + o. 
- Open selected text in default $EDITOR
* tm-yank
* ymux-jump
* tmux-sessionist
* tmux shell set to zsh w/ slightly different powerline10k
* tpm = tmux plugin manager
* initially set to asciiaquarium,
but I will change it to cmatrix soon enough.
* rebound ctrl b to ctrl a Naturally fits my hanf better.
* full mouse and paste support
* gruvbox color scheme
    - As are most of my vim/nvim colorschemes for consistency.
* pane window numbering set to start with one
