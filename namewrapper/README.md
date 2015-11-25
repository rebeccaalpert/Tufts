# namewrapper

Takes text input via textarea. When form is submitted, each line is wrapped in a hard-coded element.

Performs some basic data sanitization:
* Removal of leading and trailing spaces
* Removal of empty lines and lines with a single space (lines with multiple spaces and no text still go through, though, because I'm lazy)
* Removal of special characters (now more resistant to cross-site scripting attacks!)
