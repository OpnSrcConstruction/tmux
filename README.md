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

## Some of my favorite Tmux features:
  - prefix + ? show ALL hotkeys
  - prefix + p(revious)/n(ext)
  - prefix + c create new tab(window)
  - prefix + & close current tab.
  - prefix + 1-9move to tab
  - prefix + w show tabs+sessions menu
  - prefix + z zoom tab in/out of a pane
  - prefix + ! move pane into full window(tab)
  - prefix + x close current pane
  - prefix + " split tab(window) vertically
  - prefix + % split tab(window) horizontally
  - prefix + - delete most recently yanked text.
  - prefix + : show tmux prompt
  - prefix + {} move current pane Left({})/Right(})
  - prefix + s choose from session menu
## Copy Mode
  - prefix + [ enter copy Mode
    - When in copy mode h-j-k-l + w/b to move by chars or words L/R
    - similar to vim G(bottom of the buffer) & g(top of the buffer)
    - Also during copy mode /|?+n/N to search just like in the man pages
    - q to quit just like man
    - space during copy mode starts the copy selection
    - enter finishes selecting the text you want to copy.
    - prefix + ] pastes the most recent buffer.
    - prefix + = choose what to paste from a menu with previews.
