Vim Config Cheetsheet
============================

This cheatsheet gives you a quick guide to the extra features in this Vim config.
If you are really really new to Vim, you might want to try [the OpenVim tutorial](http://www.openvim.com/tutorial.html)
or run the `vimtutor` command

Objects, Commands & Modifications
---------------------------------

Keys                | Function
--------------------------------------------------------------------------------------------
  `%`               | Ruby scope (ie. if/else/end)
  `<leader>s`       | Collapse current ruby scope (ie. make an if/else block into a ternary)
  `<leader>S`       | Expand current ruby scope (ie. make a ternary ionto an if/else block)
  `<leader>a=`      | Align the selected lines by =
  `<leader>a=>`     | Align the selected lines by =>
  `<leader>a,`      | Align the selected lines by ,


Display options
---------------

Keys                | Function
----------------------------------------------------------------------------------------------------------
  `Ctrl``n`         | Toggle between Absolute and relative line numbers. Useful when moving blocks of text
  `<space>``p`      | Projector mode; use large, black-on-white text.
  `<leader>ig`      | Toggle the indentation guides
