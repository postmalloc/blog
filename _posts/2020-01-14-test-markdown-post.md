---
toc: false
layout: post
description: Ideas and commands on Emacs that I find useful. Most points come from the emacs inbuilt tutorial.
categories: [markdown]
title: On Emacs
---

# Insights
1. Control and Meta are parallels. `C` acts on elementary structures like letters and symbols, but `M` acts on higher level structures like words and sentences.
2. Three reasons why `C-f/b/n/p` need to be learnt - 
	1. They work on all kinds of terminals
	2. These tend to be faster after practice
	3. Forms basis for more advanced commands
3. Some commands like `C-x C-l` are disabled for beginners. Use spc to say yes.
4. Commands starting with `C-x` mostly deal with windows, files, buffers, etc.
5. Overridden behavior of keys is called being *electric*.
6. Killed text can be yanked later. Deleted text cannot be yanked. Commands that remove a lot text generally kill it - so that it can be yanked if needed. Single character removals and space removals are deletions and cannot be yanked.
7. Use `C-x C-c` when you need to logout
8. Autosave file begins and ends with a #. To recover, `M-x recover-this-file <Ret>`
9. Most commands do the "same job" in different modes but behave slightly differently
10. To exit recursive editing, do esc-esc-esc. `C-g` only exits current editing level.

# Commands

Command  | Action
----------|---------
`C-h t`  | open tutorial
`C-v`      | scroll page down
`M-v`      | scroll page up
`C-f`      | move forward 1 char
`C-b`      | move backward 1 char
`C-n`      | move down 1 line
`C-p`      | move up 1 line
`C-l`      | recenter line
`M-f`      | move forward 1 word
`M-b`      | move backward 1 word
`C-a`      | jump to beginning of line
`C-e`      | jump to end of line
`M-a`      | jump to beginning of sentence
`M-e`      | jump to end of sentence
`M-<`      | jump to top of file
`M->`      | jump to end of file
`C-u 8 C-f` | move forward 8 chars
`M-5 M-f` | move forward 5 words
`C-u 5 C-v` | scroll down 5 lines
`C-g`      | cancel current command
`C-x 1`  | one window
`C-h k C-f` | open help pane on `C-f`
`M-<DEL>` | delete word before cursor
`M-d`      | delete word after cursor
`C-k`      | kill to end of line
`M-k`      | kill to end of sentence
`C-<spc>` | mark start of selection
`C-w`      | kill selection
`M-w`      | save to kill-ring
`C-/`, `C-_`, `C-x u`      | undo
`C-x C-f` | visit file
`C-x C-s` | save file
`C-x C-b` | list buffers
`C-x b`  | goto buffer
`C-x s`  | save some buffers
`C-x u`  | undo
`M-x replace-string` | replace string
`M-x text-mode` | enter text mode
`M-x auto-fill-mode` | wrap lines
`C-x f`  | set margin (=70)
`C-s`      | incremental search
`C-r`      | incremental search reverse
`C-x 2`  | split window
`C-o`      | move to other window
`C-M-v`  | scroll other window
`C-x 4 C-f` | find file in other window
`C-x 5 2` | create new frame
`C-x 5 0` | remove selected frame
`C-h c C-f` | help on sequence commands
`C-h f list-packages` | help on function
`C-x h`  | select whole buffer
