# A Basic Guide to Emacs

This guide introduces the most basic and useful Emacs commands.



## Interpreting Commands

C is the Control key.

M is the Meta key (usually the Alt key on Windows and Linux, and the Option or Command key on Mac).

Some command examples:

**C-x C-c**: Hold Control, press X, press C, release Control

**C-x b**: Hold Control, press X, release Control, press B

**C-s [string] Enter**: Hold Control, press S, release Control, write a string, press Enter



## Basics

**C-g**: cancel the current command

**C-x C-c**: quit emacs

**M-x [command name] Enter**: execute [command name]



## Buffers

**C-x C-f**: open file in new buffer (creates the file if it doesn't exist)

**C-x C-s**: save buffer

**C-x b [buffer name] Enter**: switch to [buffer name]

**C-x k**: close buffer



## Navigation

*Go to...*

**C-v**: next screen

**M-v**: previous screen

**C-a**: beginning of line

**C-e**: end of line

**C-f**: next character

**C-b**: previous character

**C-n**: next line

**C-p**: previous line



## Text

**C-w**: cut

**M-w**: copy

**C-y**: paste

**C-x h**: select all

**C-Space**: start selection

**C-x u**: undo

**Backspace**: delete previous character

**C-d**: delete next character

**M-Backspace**: delete previous word

**M-d**: delete next word



## Search

**C-s [string] Enter**: search forward for [string]

**C-r [string] Enter**: search backward for [string]

**M-% [string1] Enter [string2] Enter**: replace [string1] with [string2] (for each instance, press Y to replace or N to skip)



## Frames

**C-x 0**: close frame

**C-x 1**: close all other frames

**C-x 2**: split frame horizontally

**C-x 3**: split frame vertically

**C-x o**: switch to next frame