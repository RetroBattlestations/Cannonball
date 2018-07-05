This is the program for the eighth RetroBattlestations BASIC
challenge. In here you'll find a simple BASIC program that plays a
game called "Cannonball". The goal is to catch the ball in your
cup. The velocity is randomly chosen and you can change the angle of
the cannon before firing. After firing try to move the cup to catch
the ball. Miss three times and it's game over!

For more details about the challenge, check out the post here:

  https://redd.it/8w49tm

## Porting ##

The code should be fairly straightforward to port. I started with a
simple ASCII version on the Apple II and didn't use any kind of dirty
tricks. Feel free to add graphics or other features, check
Enhancements.txt for more ideas.

See [List of Computers With On-Board BASIC](https://en.wikipedia.org/wiki/List_of_Computers_With_On-Board_BASIC)

## Typing Tips ##

When typing the program in you can leave off any lines which begin
with REM, they are not needed for the program to run. On many
platforms you can leave out the whitespace between keywords and
operators. IBM BASIC is not one of those however.

*Note*: On the TRS-80 Color Computer and BBC Micro you need to include
      the spaces around any IF, AND, OR, or THEN statement.

If you make a mistake and don't want to retype the entire line, most
of the BASICs have a way to make corrections.

### Amstrad CPC (464/664/6128/464+/6128+) ###

  On Amstrad CPC, use AUTO to start typing commands. Use the arrow keys
  to move about the line. Exit the AUTO mode py pressing Escape. You can
  also start on a specific line by entering AUTO 100 (for line 100).

  To go to the start or the end of the line use CONTROL+Arrow keys. You
  can also use SHIFT+Arrow keys to use the copy cursor. This is a second
  cursor that you move independendly, and will copy whatever is under it
  to the main cursor when you press COPY.

### Apple II computers ###

  On an Apple II+ use LIST <line number> to print the line with an
  error, then use ESC followed by A/B/C/D to move the cursor one step
  at a time. Position the cursor at the beginning of the line, then
  use the right arrow to move over the line and fix the error. Be sure
  to arrow all the way to the end of the entire line before you hit
  RETURN!

  On an enhanced Apple IIe, Apple IIc, or Apple IIgs you can also use
  ESC with the arrow keys. In 80 column mode (enter with PR#3) the
  cursor will change to a white block with a + in it, push ESC to drop
  out of movement mode.

### BBC Micro ###

  Use LIST <line number> to print the line with a mistake, then use
  the arrow keys to move up to the beginning of the line. Each press
  of the copy key will type in the character under the cursor. Make
  any necessary edits by just typing on the keyboard and using copy to
  avoid retyping everything.

### Commodore 64, Plus/4, and 128 ###

  Like the others, use LIST <line number> to display the line with
  problems, then use the arrow keys to move up and make any
  corrections. By pressing shift-INST you can insert a blank character
  if you missed something. Unlike the Apple II you don't need to arrow
  to the end of the line before pushing RETURN.

### TRS-80 model 100 ###

  This has to be the best built-in BASIC editor I've seen so far! Just
  type EDIT and the entire BASIC program will be loaded into the
  built-in word processor where you can make any changes you
  want. Press F8 to exit the editor and go back to BASIC.

### IBM Cassette BASIC, Disk BASIC, Advanced BASIC, GW-BASIC ###

  Type EDIT <line number> and it will print the line on the screen and
  put your cursor at the beginning of the line. Arrow left/right and
  you can use Insert & Delete to make corrections. Like Commodore
  BASIC, you don't need to arrow to the end of the line before pushing
  RETURN.

### TI-99/4A Extended BASIC ###

  Type the line number and then arrow up (FCTN+E) and it will enter
  edit mode with that line loaded.  You can move within the line with
  arrow left (FCTN+S) and arrow right (FCTN+D) and move to the
  previous or next line with arrow up (FCTN+E) or arrow down (FCTN+X).
  You can delete the character under the cursor with DEL (FCTN+1) or
  turn on insert mode to insert extra characters with INS (FCTN+2).
  You do not need to move to the end of the line before pressing
  ENTER.

### ZX Spectrum Sinclair BASIC ###

  As with other systems, use LIST <line number> to display the line with
  the error, or use Up and Down arrow (CAPS SHIFT-7 and CAPS SHIFT-6
  respectively) to select the line, shown by a > characater immediately
  to the right of the line number, then press CAPS SHIFT and 1 (for EDIT).
  This will display the line at the bottom of the screen where you can
  use left and right arrows (CAPS SHIFT-5 and CAPS SHIFT 8 respectively)
  to move to the error and correct it. Typing will insert characters at
  the cursor, press DELETE (CAPS SHIFT 0) to delete the character to the
  left of the cursor. Like Commodore and IBM BASICs, you don't need to
  move to the end of the line before pressing ENTER.
