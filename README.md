Repositories for dot files, including executables
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

For new disk do:

sudo apt-get update && sudo apt-get dist-upgrade
sudo apt-get install build-essential



PYTHON_DOWNLOAD_URL=https://www.python.org/ftp/python/$PYTHON_VERSION/Python-3.6.5.tgz
wget "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-3.6.5.tgz" -O python.tar.tgz


TMUX Note
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
ctlr+b ===> %                               # Split panes horizontally
            "                               # Split panes vertically
            dpad                            # Move between panes
            c                               # Create new windows
            p                               # Switch to previous windows
            n                               # Switch to next windows
            d                               # Detach current session
            D                               # Detach current session with choice ???
            z                               # Make a pane full screen / return to a normal size
            ctrl + dpad                     # Resize pane according to arrow direction
            ,                               # Rename current windows
            x                               # Close a session         
            
            : ===> new -s <name>                              # Create new session
                   set status-style "bg=colour240"            # Change status bar color
         
            
            
            
            
tmux ls                                     # List of running sessions
tmux attach -t 0                            # Connect to a running session
tmux rename-session -t <oldname> <newname>  # Rename a session name

            

ctrl+d / type: exit   # Close panes
