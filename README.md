# A Basic Slate Setup

## Overview
Credit for most of this config and tutorial goes to
Jed Northridge, his github page is [jedcn](https://github.com/jedcn).
View his excellent introduction to slate tutorial
[Here](https://github.com/jedcn/getting-started-with-slate).

**If you have a basic working knowledge of slate and just want a basic config then
you're welcome to just use what's here. The mappings I'm using are listed
below**

<hr></hr>

Otherwise, if you *have* heard of [Slate](https://github.com/jigish/slate)
before, but found it inaccessible because it describes itself as:

> a bit daunting to get configured

Or, if you *have not* heard of [Slate](https://github.com/jigish/slate)
before, but you are using MacOS **and**:

* You find it slightly irritating whenever you manually adjust the
  height and width of windows using a mouse

* You find yourself with a two display setup and you wish you could
  press a button and have an application jump between displays

* You find yourself pressing COMMAND + CONTROL to switch between
  applications, but sometimes you let go before you reach the one you
  want and have to start over again, or perhaps you "go past" the one
  you want and have to loop through again.

**Then you should read [Jed's Tutorial](https://github.com/jedcn/getting-started-with-slate) before continuing here!**

He'll get you up and running in 15 minutes or so.

<hr></hr>

I've updated Jed's setup to include the h and ' keys for window
manipulation. 

I also changed the window switching hinting mechanism 
so it uses keys on the right hand. I feel this is more convenient,
since you'll be hitting ctrl + cmd with your left. 

Bindings used:

**Moving applications to different displays:**

cmd + ctrl
<table>
  <tr>
    <td>
      1
    </td>
    <td>
      2
    </td>
    <td>
      3
    </td>
  </tr>
</table>

**Moving applications within a display**

cmd + ctrl
<table>
  <tr>
    <td>

    <\td>
    <td>
      u
    </td>
    <td>
      i
    </td>
    <td>
      o
    </td>
    <td>

    <\td>
    <td>

    <\td>
  </tr>
    <tr>
    <td>
      h
    <\td>
    <td>
      j
    </td>
    <td>
      k
    </td>
    <td>
      l
    </td>
    <td>
      ;
    <\td>
    <td>
      '
    <\td>
  </tr>
    <tr>
    <td>

    <\td>
    <td>
      m
    </td>
    <td>
      ,
    </td>
    <td>
      .
    </td>
    <td>
    <td>

    <\td>

    <\td>
  </tr>
</table>

<table>
  <tr>
    <td>

    <\td>
    <td>
      |
    </td>
    <td>
      T
    </td>
    <td>
       ̅ ̅ |
    </td>
    <td>

    <\td>
    <td>

    <\td>
  </tr>
    <tr>
    <td>
      | - 5/8
    <\td>
    <td>
      | -
    </td>
    <td>
      +
    </td>
    <td>
      - |
    </td>
    <td>
      switch
    <\td>
    <td>
      3/8 - |
    <\td>
  </tr>
    <tr>
    <td>

    <\td>
    <td>
      |_
    </td>
    <td>
      ⊥
    </td>
    <td>
      _|
    </td>
    <td>
    <td>

    <\td>

    <\td>
  </tr>
</table>

The bindings described:

* Misc
  * ```COMMAND + CONTROL + k``` = maximize current window
  * ```COMMAND + CONTROL + ;``` = open window switching interface

* Corners
  * ```COMMAND + CONTROL + u``` = upper left corner
  * ```COMMAND + CONTROL + o``` = upper right corner
  * ```COMMAND + CONTROL + m``` = bottom left corner
  * ```COMMAND + CONTROL + n``` = bottom left corner (n instead of m is an easy typo)
  * ```COMMAND + CONTROL + u``` = bottom right corner

* Halves
  * ```COMMAND + CONTROL + i``` = top half of screen
  * ```COMMAND + CONTROL + l``` = right half of screen
  * ```COMMAND + CONTROL + ,``` = bottom half of screen
  * ```COMMAND + CONTROL + j``` = bottom left of screen

* More movement
  * ```COMMAND + CONTROL + h``` = left 5/8ths of the screen
  * ```COMMAND + CONTROL + '``` = right 3/8ths of the screen

* Display switching
  * ```COMMAND + CONTROL + 1``` = move window to first display
  * ```COMMAND + CONTROL + 2``` = move window to second display
  * ```COMMAND + CONTROL + 3``` = move window to third display


