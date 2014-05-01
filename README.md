screen-layouts
==============

A set of GNU Screen layouts made simple

Configuration
-------------

Just add to your .bashrc or .bash\_profile the following lines

```
# GNU Screen Layouts Aliases
. ABSOLUTE_PATH_TO_PROJECT/screenAlias.sh
```

Usage
-----

In your bash terminal just use the following commands

```
# Invokes an Screen of 1 row  x 2 columns 
screen12 

# Invokes an Screen of 2 rows x 1 column
screen21 

# Invokes an Screen of 2 rows x 2 columns
screen22 

# Invokes an Screen of 1 row  x 4 columns
screen14 

# Invokes an Screen of 4 rows x 1 column 
screen41 
```

GNU Screen CheatSheet
---------------------

This is a little hint on extra params

```
<command> -R MySession    # Creates a screen named by MySession or loads it if exists already

screen -ls                # List currently active Screen Sessions
```

This is a little hint on useful shortcuts once inside a screen

```
ctrl-a TAB     # Switch the input focus to the next region.

ctrl-a S       # Split the current region horizontally into two new ones.

ctrl-a |       # Split the current region vertically into two new ones.

ctrl-a k       # Destroy current window.

ctrl-a c       # Create a new window with a shell and switch to that window.

ctrl-a ctrl-\  # Kill all windows and terminate screen.
```

You can find the full manual in [here](http://www.gnu.org/software/screen/manual/screen.html "GNU Screen Command Manual").
