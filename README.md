Arduino-BBEdit
==============

A fork of Carlyn's excellent Codeless Language Module, to fix a bug that annoyed me.
For the original, see here:
  https://github.com/carlynorama/Arduino-BBEdit

In this version, you *can* include characters ' " { } in comments
without borking BBEdit's ability to recognise function definitions.

It's a tiny change to the code, but it makes me happy.

To use:

Copy the Arduino.plist file to the folder below, and restart BBEdit.
  /Users/<youruserid>/Library/Application Support/BBEdit/Language Modules/
