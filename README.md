# A Basic Slate Setup

## Overview
Credit for much of this config and tutorial goes to
Jed Northridge, his github page is [jedcn](https://github.com/jedcn).
View his excellent introduction to slate tutorial
[Here](https://github.com/jedcn/getting-started-with-slate). 

**What Is Slate?**

Slate is a window manager for Mac OSX which allows you to use your
keyboard to move, resize and switch between windows. 

**My Config**

The goal of this config is to provide a window manager setup which 
is simple and intuitive, yet powerful.

Bindings used:

**Switching between open applications**

cmd + ctrl &:

<table>
  <tr> 
    <td>

    </td>
    <td>
       i
    </td>
    <td>

    </td>
  </tr>
  <tr>
    <td>
      j
    </td>
    <td>
      k
    </td>
    <td>
      l
    </td>
  </tr>
  <tr>
    <td>
       
    </td>
    <td>
       ,
    </td>
    <td>
       
    </td>
  </tr>
</table>

Switch direction:

<table>
  <tr> 
    <td>

    </td>
    <td>
      ↑
    </td>
    <td>

    </td>
  </tr>
  <tr>
    <td>
     ← 
    </td>
    <td>
      ⊙
    </td>
    <td>
      →
    </td>
  </tr>
  <tr>
    <td>
      
    </td>
    <td>
      ↓
    </td>
    <td>

    </td>
  </tr>
</table>

The k key shows whatever window is behind the current one.  The rest of the keys listed move focus in the arrow-indicated direction.

cmd + ctrl &:
<table>
  <tr>
    <td>
     ' 
    </td>
  </tr>
</table>

to bring up a prompt that will allow you to switch to any window you have open.


**Moving applications within a display**

cmd + ctrl + alt &:
<table>
  <tr>
    <td>

    </td>
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

    </td>
  </tr>
    <tr>
    <td>
      h
    </td>
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
    </td>
  </tr>
    <tr>
    <td>

    </td>
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
    </td>
  </tr>
</table>

<table>
  <tr>
    <td>

    </td>
    <td>
      ⌜
    </td>
    <td>
      ⊤ 
    </td>
    <td>
      ⌝
    </td>
    <td>

    </td>
  </tr>
    <tr>
    <td>
      ⊢ 5/8
    </td>
    <td>
      ⊢
    </td>
    <td>
      +
    </td>
    <td>
      ⊣
    </td>
    <td>
      3/8 ⊣
    </td>
  </tr>
  <tr>
    <td>

    </td>
    <td>
      ⌞
    </td>
    <td>
      ⊥
    </td>
    <td>
      ⌟
    </td>
    <td>

    </td>
  </tr>
</table>

**Moving applications to different displays:**

cmd + ctrl + alt &:
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


**Full description of bindings**

* Switching Between Windows
  * Directional
    * ```COMMAND + ALT + i``` = quick-switch to window above the current one
    * ```COMMAND + ALT + ,``` = quick-switch to window below the current one
    * ```COMMAND + ALT + j``` = quick-switch to window left the current one
    * ```COMMAND + ALT + l``` = quick-switch to window right the current one

  * Misc
    * ```COMMAND + ALT + '``` = open window switching interface
    * ```COMMAND + ALT + k``` = quick-switch to window behind the current one

* Moving Windows
  * Misc
    * ```COMMAND + CONTROL + ALT + k``` = maximize current window

  * Corners
    * ```COMMAND + CONTROL + ALT + u``` = move to upper left corner
    * ```COMMAND + CONTROL + ALT + o``` = move to upper right corner
    * ```COMMAND + CONTROL + ALT + m``` = move to bottom left corner
    * ```COMMAND + CONTROL + ALT + n``` = move to bottom left corner (n instead of m is an easy typo)
    * ```COMMAND + CONTROL + ALT + u``` = move to bottom right corner

  * Halves
    * ```COMMAND + CONTROL + ALT + i``` = move to top half of screen
    * ```COMMAND + CONTROL + ALT + l``` = move to right half of screen
    * ```COMMAND + CONTROL + ALT + ,``` = move to bottom half of screen
    * ```COMMAND + CONTROL + ALT + j``` = move to bottom left of screen

  * More movement
    * ```COMMAND + CONTROL + ALT + h``` = move to left 5/8ths of the screen
    * ```COMMAND + CONTROL + ALT + ;``` = move to right 3/8ths of the screen

* Display switching
  * ```COMMAND + CONTROL + 1``` = move window to first display
  * ```COMMAND + CONTROL + 2``` = move window to second display
  * ```COMMAND + CONTROL + 3``` = move window to third display


