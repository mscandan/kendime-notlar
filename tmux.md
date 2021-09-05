# TMUX shortcuts

## Session control
  - Start session
    ```sh
      tmux
    ```
    ```sh
      tmux new -session_name
      tmux new-session -session_name
    ```
  - Exit session
    ```sh
       exit
    ```
  - Reset tmux
    ```sh
     tmux kill-server
    ```


## prefix = ctrl + b

## Splitting
  - split horizontal = ctrl + b + %
  - split vertical = ctrl + b + "

Resizing use prefix before all the commands
  - :resize-pane -D (Resizes the current pane down)
  - :resize-pane -U (Resizes the current pane upward)
  - :resize-pane -L (Resizes the current pane left)
  - :resize-pane -R (Resizes the current pane right)
  - :resize-pane -D 10 (Resizes the current pane down by 10 cells)
  - :resize-pane -U 10 (Resizes the current pane upward by 10 cells)
  - :resize-pane -L 10 (Resizes the current pane left by 10 cells)
  - :resize-pane -R 10 (Resizes the current pane right by 10 cells)
