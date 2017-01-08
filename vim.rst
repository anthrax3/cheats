+++
title = "Vim"
+++

Core
----

``<C>-o``
  in insert mode switch to normal for 1 command

Marks
-----

``ma``
  toggle marks

``m-``
  clear all marks

``]' ['``
  jump to prev/next mark start of line


Spell
-----

``zg``
  add word
``z=``
  suggestion
``[s``
  next misspelled word
``gq``
  wrap visual selection

Folding
-------

``za / zc``
  open / close cursor fold
``zm / zr``
  global fold/unfold by 1 level
``zR``
  unfold all
``zj / zk``
  navigate between folds
``zi``
  toggle folding

Practical Vim
-------------

``c-h, c-w, c-u``
  in insert mode delete char, word or line
``aw/ap iw/ip/it``
  operator around word/paragraph or inner tag
``zz``
  middle current line
``c-r0``
  paste in insert mode without distracting
``c-r*``
  user expression register to calculate and paste
``gv``
  reselect last visual selection
