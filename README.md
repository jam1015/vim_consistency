# Consistency 

Aims to make certain vim commands more consistent.


## `Y`

In default behavior it is a synonym of `yy` yank a whole line.  This plugin makes it yank to the end of the line, consistent with `D` anc `C` which respectively delete and change to the end of a line.


## `w`

`cw` in Vim changes to the end of the current word, like `ce` does, not to the beginning of the next word like one might expect.  This plugin tries to make it behave in the naturally expected way.
