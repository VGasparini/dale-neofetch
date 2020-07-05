# Vamo dale ascii art on Neofetch

```text
                                -::=###-         
                              -*=*::- -#:          
                            =##       -#:          
                         :*+-     -***+            
                        =*      =##                
                     :*+-    :*+-                  
                    #+      =*                     
                 :*+-   ---*+:                     
                #+  -     -#:                      
             :++-:*******=#*-               +****: 
            =####+          =####*        -#:    +#
        +++*-:++++++++++-        :+++++++*+     :+*
      :#-               =##              +##:   =* 
    +*+                   -**++++:----      +++*-  
    #+                        -#:+###*        -#:  
+***-   +********+++-   -       +*+  :**+++     =* 
#+                  =###:        +#       -#####:  
#+                   :*:***+-    :*+--   +#        
#+                      =*  =*    -#:-  **         
*+:     ::::*******+-    +#  +#   -#: -#:          
 *=                 =+    -#: -#: -#:+#            
 +*:-          -     +#   -#: -=+:+*-+#            
  :#-                --#- -#:   --- =*-            
  :#-                 -=+::=-     -:*+             
   -=+              -   ---      +#-               
    #+              -        -::*+                 
    -*=              -    -##*---                  
     *=              +#   -#:                      
     *=           -==+-   -#:                      
      :#-    +=====       -#:                      
```

## Instalation

Copy art to `neofetch` folder

```bash
cp dale.txt /home/$USER/.config/neofetch/dale.txt
```

Replace alias to get `dale.txt` as ascii art

```bash
alias neofetch='neofetch --ascii /home/$USER/.config/neofetch/dale.txt'
```

## Customizing

* Change arg `${c2}` inside `dale.txt` to choose character color
* Use the version with typo `VAMO DALE` by changing `dale.txt` to `dale_2.txt` on commands
