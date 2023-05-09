# Less command
The less command helps to funnel down the files found when using the command to just a screenful of outputs that fit the desired description. Some useful notes to know when using the less command is that you are able to control the amount of content being displayed as you go along. So for instance, if you had used the less command and the page of files fitting the search come up, you can continue to scroll through the results one by one using the up and down keys on a keyboard. Or, if you'd rather go page by page you can go down an entire page of results by using the spacebar.    


**In order to exit the less command page you simply hit the q key**

## Less command line options

### Less -?
`less -?`
When this command is used in the terminal this is the output:
```
                 SUMMARY OF LESS COMMANDS

      Commands marked with * may be preceded by a number, N.
      Notes in parentheses indicate the behavior if N is given.
      A key preceded by a caret indicates the Ctrl key; thus ^K is ctrl-K.   

  h  H                 Display this help.
  q  :q  Q  :Q  ZZ     Exit.
 --------------------------------------------------------------------------- 

                           MOVING

  e  ^E  j  ^N  CR  *  Forward  one line   (or N lines).
  y  ^Y  k  ^K  ^P  *  Backward one line   (or N lines).
  f  ^F  ^V  SPACE  *  Forward  one window (or N lines).
  b  ^B  ESC-v      *  Backward one window (or N lines).
  z                 *  Forward  one window (and set window to N).
  w                 *  Backward one window (and set window to N).
  ESC-SPACE         *  Forward  one window, but don't stop at end-of-file.   
  d  ^D             *  Forward  one half-window (and set half-window to N).  
  u  ^U             *  Backward one half-window (and set half-window to N).  
  ESC-)  RightArrow *  Left  one half screen width (or N positions).
  ESC-(  LeftArrow  *  Right one half screen width (or N positions).
  F                    Forward forever; like "tail -f".
  r  ^R  ^L            Repaint screen.
  R                    Repaint screen, discarding buffered input.
        ---------------------------------------------------
        Default "window" is the screen height.
        Default "half-window" is half of the screen height.
 --------------------------------------------------------------------------- 

                          SEARCHING

  /pattern          *  Search forward for (N-th) matching line.
  ?pattern          *  Search backward for (N-th) matching line.
  n                 *  Repeat previous search (for N-th occurrence).
  N                 *  Repeat previous search in reverse direction.
  ESC-n             *  Repeat previous search, spanning files.
  ESC-N             *  Repeat previous search, reverse dir. & spanning files.
  ESC-u                Undo (toggle) search highlighting.
  &pattern          *  Display only matching lines
        ---------------------------------------------------
        A search pattern may be preceded by one or more of:
HELP -- Press RETURN for more, or q when done
```






### Less -V
`less -V`
When this command is used in the terminal this is the output:
```
less 458 (POSIX regular expressions)
Copyright (C) 1984-2012 Mark Nudelman

less comes with NO WARRANTY, to the extent permitted by law.
For information about the terms of redistribution,
see the file named README in the less distribution.
Homepage: http://www.greenwoodsoftware.com/less
```










### Less --help
`less --help`
When this command is used in the terminal this is the output:
```
    Commands marked with * may be preceded by a number, N.
      Notes in parentheses indicate the behavior if N is given.
      A key preceded by a caret indicates the Ctrl key; thus ^K is ctrl-K.   

  h  H                 Display this help.
  q  :q  Q  :Q  ZZ     Exit.
 --------------------------------------------------------------------------- 

                           MOVING

  e  ^E  j  ^N  CR  *  Forward  one line   (or N lines).
  y  ^Y  k  ^K  ^P  *  Backward one line   (or N lines).
  f  ^F  ^V  SPACE  *  Forward  one window (or N lines).
  b  ^B  ESC-v      *  Backward one window (or N lines).
  z                 *  Forward  one window (and set window to N).
  w                 *  Backward one window (and set window to N).
  ESC-SPACE         *  Forward  one window, but don't stop at end-of-file.   
  d  ^D             *  Forward  one half-window (and set half-window to N).  
  u  ^U             *  Backward one half-window (and set half-window to N).  
  ESC-)  RightArrow *  Left  one half screen width (or N positions).
  ESC-(  LeftArrow  *  Right one half screen width (or N positions).
  F                    Forward forever; like "tail -f".
  r  ^R  ^L            Repaint screen.
  R                    Repaint screen, discarding buffered input.
        ---------------------------------------------------
        Default "window" is the screen height.
        Default "half-window" is half of the screen height.
 --------------------------------------------------------------------------- 

                          SEARCHING

  /pattern          *  Search forward for (N-th) matching line.
  ?pattern          *  Search backward for (N-th) matching line.
  n                 *  Repeat previous search (for N-th occurrence).
  N                 *  Repeat previous search in reverse direction.
  ESC-n             *  Repeat previous search, spanning files.
  ESC-N             *  Repeat previous search, reverse dir. & spanning files.
  ESC-u                Undo (toggle) search highlighting.
  &pattern          *  Display only matching lines
        ---------------------------------------------------
        A search pattern may be preceded by one or more of:
HELP -- Press RETURN for more, or q when done
```










### Less -version
`less -version`
When this command is used in the terminal this is the output:
