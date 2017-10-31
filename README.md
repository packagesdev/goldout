## Synopsis

goldout does the opposite of goldin.

## Motivation

Since FixupResourceForks has been apparently removed from macOS Sierra and later, it might be useful to have a replacement.

To address some issues of FixupResourceForks, the following improvements have been made:

- it's a 32 and 64-bit binary.
- it does not use deprecated APIs.
- it does not assume there are both FinderInfo and Resource Fork entries in the AppleDouble file.
- the source code is available.
- long options are called with --

Minimum OS requirement is Mac OS X 10.8 at this time.

## Usage

	$ goldout [options] file ...
	
	  Options:
	  --help, -h           Show this usage guide
	  --quiet, -q          Do not display the list of processed files
	  --nosetinfo          Do not set the FinderInfo
	  --nodelete           Do not delete the AppleDouble file
	  --version            Show the version of this tool

As with FixupResourceForks, if no files are provided, / will be used.

## Tests

Description forthcoming

## License

Copyright (c) 2017, Stephane Sudre
All rights reserved.
 
Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
 
- Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
- Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
- Neither the name of the WhiteBox nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.
 
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED.  IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
 