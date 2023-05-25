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










### Less -s (filename)  
`less -s biomed`
When this command is used in the terminal this is the output:
```  
total 30316
drwxr-s--- 2 cs15lsp23dw ieng6_cs15lsp23  65536 May  8 20:07 ./
drwxr-s--- 6 cs15lsp23dw ieng6_cs15lsp23   4096 May  8 20:19 ../
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  24112 May  8 20:07 1468-6708-3-1.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  29585 May  8 20:07 1468-6708-3-10.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  16882 May  8 20:07 1468-6708-3-3.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  31378 May  8 20:07 1468-6708-3-4.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  18114 May  8 20:07 1468-6708-3-7.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  24028 May  8 20:07 1471-2091-2-10.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  35103 May  8 20:07 1471-2091-2-11.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  24851 May  8 20:07 1471-2091-2-12.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  27970 May  8 20:07 1471-2091-2-13.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  18716 May  8 20:07 1471-2091-2-16.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  45414 May  8 20:07 1471-2091-2-5.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  25458 May  8 20:07 1471-2091-2-7.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  25298 May  8 20:07 1471-2091-2-9.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  29139 May  8 20:07 1471-2091-3-13.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  54849 May  8 20:07 1471-2091-3-14.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  34209 May  8 20:07 1471-2091-3-15.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  35953 May  8 20:07 1471-2091-3-16.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  29469 May  8 20:07 1471-2091-3-17.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  40558 May  8 20:07 1471-2091-3-18.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  40379 May  8 20:07 1471-2091-3-22.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  33815 May  8 20:07 1471-2091-3-23.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  34168 May  8 20:07 1471-2091-3-30.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  56000 May  8 20:07 1471-2091-3-31.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  52697 May  8 20:07 1471-2091-3-4.txt*   
biomed
```  
When this command had been run the current directory was technical. As displayed above the command shows a small preview of the available files within the named folder. If you wish to leave afterwards, you hit the q key.









`less -s 1468-6708-3-1.txt`
When this command is used in the terminal this is the output:  
```  

        Introduction
        Older adults are frequently counseled to lose weight,
        even though there is little evidence that overweight is
        associated with increased mortality in those over age 65.
        Six large controlled population-based studies of
        non-smoking older adults have investigated the association
        between body mass index (BMI) and mortality, controlling
        for relevant covariates [ 1 2 3 4 5 6 ] . All studies found
        excess risk for persons with very low BMI, but that persons
        with moderately high BMI had little or no extra risk except
        in certain small subsets. A review of 13 studies of older
        adults drew similar conclusions [ 7 ] .
        Many healthy older adults report gradual weight gain
        throughout adult life. It may be that a small amount of
        gradual weight gain is normative and associated with the
        most robust health as we age. It has been suggested that
        weight standards be adjusted upwards for age [ 8 ] . Such
        recommendations remain controversial, however, because the
        number of studies of older persons is fairly small, and
        because few studies have examined the relation of BMI to
        quality of life or years of healthy life (YHL) in the
        elderly [ 9 ] .
        In older adults, risk factors may have a greater effect
1468-6708-3-1.txt
```  
What this command does is it shows a small sample of the given text file. For this particular command, one would have to change their current directory to be in biomed, not technical. After doing so, the command above displays the the first small bit of the desired text file. If you wish to exit, simply hit the q key.   





