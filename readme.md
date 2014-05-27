Tag-ST2
======
This package ([Tag-ST2](http://www.sublimetext.com/)) is a fork of the official [ST/Tag](https://github.com/SublimeText/Tag) plugin for ST3.  I'll be backporting bug fixes from the official ST3 branch and trying to keep this working on ST2.


Installation
------------------
+ Windows
  + cd %APPDATA%/Sublime Text 2/Packages
  + git clone git@github.com:xstherrera1987/Tag-ST2.git Tag
  + restart sublime

+ OSX
	+ cd  ~/Library/Application Support/Sublime Text 2/Packages
	+ git clone git@github.com:xstherrera1987/Tag-ST2.git Tag
	+ restart sublime

+ Linux
  + cd  ~/.Sublime Text 2/Packages
  + git clone git@github.com:xstherrera1987/Tag-ST2.git Tag
  + restart sublime

+ then...
  + Hope it Works


Description
------------------
The following is from the original plugin:


---

Close tag on slash
------------------

A command that is meant to be bound to the slash ("/") key in order to semi auto close open HTML tags (in part inspired by the discussion at http://www.sublimetext.com/forum/viewtopic.php?f=5&t=1358).
Requires build 2111 or later of Sublime Text 2.

*Usage*

Runs automatically when inserting an Slash "/" into an HTML document.

Tag Indent
------------------

Apply and/or add beauty indentation to HTML/XML/RDF/XUL tags found on selection(s).

*Aims*

Aims to add and/or apply correct indentation to little portions of HTML or XML, not to complete documents.

*Usage*

There is context menuitems called "Indent Tags on Selection", "Indent Tags on Document"

There is also Main menuitems: Edit -> Tag -> "Indent Tags on Selection", "Indent Tags on Document"

There is also commands "Indent Tags on Selection", "Indent Tags on Document"

*Information*

It takes the starting "indentation level" from the first line of each selection and sums tabs as needed.

On empty tags, and on tags with less than 60 characters, it writes the tag in one line.

Short-cut is "ctrl+alt+f"

Tag Remove
------------------

Provides the ability to remove all tags or some selected tags in a document or in selection(s).

*Usage*

The main menu "Edit" -> "Tag" provide access to the commands

Insert As Tag
------------------

Converts the current word to an html-tag. If there is no current word, a default tag is inserted.

*Usage*

The short-cut is "ctrl+shift+,"

Tag Remove Attributes
------------------

Allows to remove attributes from tags for selection or document.

*Usage*

The main menu "Edit" -> "Tag" provide access to the commands

Tag Close
------------------

Overwrite the built-in funtionallity by a custom one provided by this package which fix some bugs.

*Usage*

Windows, Linux : ALT+.
OSX : SUPER+ALT+.

Tag Lint
------------------

Experimental feature which aims to check correctness of opened and closed tags.

*Usage*

The main menu "Edit" -> "Tag" -> "Tag Lint"
