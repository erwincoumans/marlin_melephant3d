# Marlin firmware for Makeblock mElephant 3D printer

The original zip file from Makeblock didn't work for me.
(http://www.makeblock.cc/melephant-3d-printer/#comment-2264715033)
This is a version with minor changes to make it compile using the Arduino IDE.

## Build instructions 

Install Arduino IDE (tested with version 1.6.7)
Copy U8lib directory to Arduino/libraries folder
Open Marlin/Marlin.ino using the Marlin IDE and compile/upload to mElephant 3D using USB cable

## License

    Reprap firmware based on Sprinter and grbl.
 Copyright (C) 2011 Camiel Gubbels / Erik van der Zalm

 This program is free software: you can redistribute it and/or modify
 it under the terms of the GNU General Public License as published by
 the Free Software Foundation, either version 3 of the License, or
 (at your option) any later version.

 This program is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU General Public License for more details.

 You should have received a copy of the GNU General Public License
 along with this program.  If not, see <http://www.gnu.org/licenses/>.
 */

/*
 This firmware is a mashup between Sprinter and grbl.
  (https://github.com/kliment/Sprinter)
  (https://github.com/simen/grbl/tree)

 It has preliminary support for Matthew Roberts advance algorithm
    http://reprap.org/pipermail/reprap-dev/2011-May/003323.html


