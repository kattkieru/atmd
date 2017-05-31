# Affinix Tile/Map Designer
by Hideaki Omuro

I was curious about this, so I've added a build script and embedded
SDL 1.2.15 in the repo.  It builds and starts, but I have no idea 
yet how to use it.

## Building
~~~~
mkdir build
cd build
cmake ..
cmake --build .
~~~~

## Usage
`atmd file.ats file.amp [/T:tile.bin] [/M:map.bin] [/P:file.pal]`

## License
Copyright (C) 2000 Affinix Software

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
