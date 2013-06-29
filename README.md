# Random Text

A package for Sublime Text that will generate random strings of arbitrary length and character sets.

## Installation

### Package Control

Random Text is available via [Will Bond's Package Control](http://wbond.net/sublime_packages/package_control)

### Using Git

Go to your Sublime Text `Packages` directory and clone the repository:

    git clone https://github.com/dallbee/RandomText.git "Random Text"

## Usage

To generate string, go to `Tools >> Random Text >> Generate`.
You may also use the keybinding `Ctrl + Shift + R` (Linux/Windows) or `Command + Shift + R` (OSX)

To specify a character set go to `Tools >> Random Text >> Charset` and select an item from the list, or set a custom set by going to `Tools >> Random Text >> Charset >> Custom` and typing in your own string of characters for the generator to use.

To specify a length go to `Tools >> Random Text >> Length` and select an item from the list, or set a custom length by going to `Tools >> Random Text >> Length >> Custom` and typing in your own length at the prompt.

## Notes

- Default charset: Printable
- Default length: 32
- The printable charset does not contain whitespace characters or quotations, for ease of use whilst programming.

## Author

Written by Dylan Allbee

## Credit

Phalanxia from ##XAMPP on FreeNode for his help with testing

[Shawn Butts](https://github.com/shawnbutts) for adding support for configuration files 

## BSD 2-Clause License

Copyright (c) 2013, Dylan Allbee
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
