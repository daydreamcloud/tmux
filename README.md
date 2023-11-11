# TMUX Basic
#
## open a new session
#tmux

## Creating Named Tmux Sessions: 
#tmux new -s [session_name]

## Detaching from Tmux Session:
- Ctrl+b d

## Get a list of the currently sessions type:
#tmux ls

## Attach to session, you would type:
#tmux attach-session -t [session_name]

## Common commands for managing Tmux windows and panes:
- Ctrl+b c Create a new window (with shell)
- Ctrl+b w Choose window from a list
- Ctrl+b 0 Switch to window 0 (by number )
- Ctrl+b , Rename the current window
- Ctrl+b % Split current pane horizontally into two panes
- Ctrl+b " Split current pane vertically into two panes
- Ctrl+b o Go to the next pane
- Ctrl+b ; Toggle between the current and previous pane
- Ctrl+b x Close the current pane

## Get list of all commands:
- Ctrl+b ?
