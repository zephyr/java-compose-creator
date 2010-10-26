# Compose Creator

## Purpose

This is a simple Java program to to convert the latest version of the unicode standard into fitting compose definitions for a linux system.

## How to create the `unicode.modul`
At first, you’ll have to install a Java 6 JRE or later (if you doesn’t already have one).

At second, download the file [UnicodeData.txt](http://unicode.org/Public/UNIDATA/UnicodeData.txt)  (you should always download it yourself to get the latest version).

Now switch to your command-line interface and type

		javac UnicodeModul.java
		java UnicodeModul

## How to use the `unicode.modul`
It contains a list of combose comination for all unicode codepoints (0x0-0x10FFFD) with the hex value of the codepoint as key, for example

		<Multi_key> <u> <u> <4> <7> <c> <space> : "Ѽ" U047c # CYRILLIC CAPITAL LETTER OMEGA WITH TITLO

or for short: `♫uu47c=Ѽ`.

Just append them to the `~/.XCompose` file of your GNU/Linux OS.

## Licence

Copyright 2010 by [Dennis Heidsiek](http://www.google.com/profiles/Dennis.Heidsiek)

This program is free software: you can redistribute it and/or modify it under the terms of the [GNU General Public License](http://www.gnu.org/copyleft/gpl.html) as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see [here](http://www.gnu.org/licenses/).
