In addition to FOSS I have commercial PDF comparison products, in particular:
- [DiffPDF for Windows](https://www.qtrac.eu/diffpdf.html) an easy-to-use GUI application, and
- [comparepdfcmd for Windows](https://www.qtrac.eu/comparepdfcmd.html) a command line/console tool ideal for scripting and testing use.

**In view of the EU’s Cyber Resilience Act and an abundance of caution, I
have withdrawn all my free software (see
[EU CRA](https://en.wikipedia.org/wiki/Cyber_Resilience_Act#Criticism)).**

All the FOSS below has been withdrawn.

### Go Tools

- *minicalc* is an FLTK-based GUI tool that provides an evaluating calculator, a Go regex tester, length conversions, keyboard accelerator hints generator for GUI applications, and some static data (e.g., ASCII codes).
- *sfind* is a file find command line tool (like Unix's `find` but _much_ easier to use because it has _much less_ functionality). I find it sufficient as a complete `find` replacement.
- *unz* an archive unpacking command line tool that never creates more than one file or folder in the current folder. If the archive contains multiple files or folders unz creates a subfolder to contain them all.
- *murmur* is an Unlimited Register Machine (URM) emulator with optional extensions (indirect addressing and some extra convenience commands).

### Go Libraries

- *accelhint* is a library for generating keyboard accelerators for a list of strings (e.g., menu items or dialog buttons and labels).
- *clip* is another Go command line interface (argument) parser since I really dislike the standard library's `flag` package.
- *go-diff* is a generic sequence matcher library based on the Python `difflib` algorithm.
- *gong* is a library providing many small useful functions that I use in most Go applications.
- *gset* is a library providing a generic set implementation.

### UXF (Uniform eXchange Format)

*UXF* is a plain text human readable optionally typed storage format. UXF is designed to make life easier for software developers and data designers. It directly competes with csv, ini, json, toml, and yaml formats. One key advantage of UXF is that it supports custom (i.e., user-defined) types. This can result in more compact, more readable, and easier to parse data. And in some contexts it may prove to be a convenient alternative to sqlite or xml. A Python
library is available.

### TDB (Text DataBase format)

This is a plain text human readable strictly typed alternative to CSV. I have written libraries in
*Go* and *Python*. This format is much simpler (and less versatile) than UXF, so easier to implement and easier to use.

### Gravitate Game

Only the online [Gravitate JavaScript](https://www.qtrac.eu/gravitate.html) version is available now.

*Gravitate* is a SameGame/TileFall-like game.
I have created versions of this game in many different languages using various GUI libraries, but the Rust/FLTK one is by far the best.
The repo includes a 1.9MB Windows binary (64-bit).
The source can be used to build on Linux and on Windows (32- or 64-bit).

### AMP 
*“Another Music Player”*
This provides a basic but useful example of Rust/FLTK andthe Soloud sound library.
It should be especially handy for audio books since at startup it restores
the last played track at the exact position it had reached.
The repo includes a 2.5MB Windows binary (64-bit).
The source can be used to build on Linux and on Windows (32- or 64-bit).

### CharFind
*CharFind* is an application for finding Unicode characters.
The repo includes a 1.9MB Windows binary (64-bit).
The source can be used to build on Linux and on Windows (32- or 64-bit).

### XindeX

*XindeX* is an easy to learn and use GUI application for creating, editing, and outputting indexes (e.g., for books).

This has been tested on Windows and Linux and is written in Python 3 (>=3.6) using PySide 1 (Qt 4.8).

### Retest

*Retest* is an easy to use application (and Rust library) for automating black box regression testing on Windows and Unix.

### Diff Libraries

The Python standard library includes the `difflib` module which has an excellent sequence matcher to find and report the differences between two sequences (e.g., between two sequences of lines). I've ported a version of this functionality to D, Nim, Rust, and Go.

### Other tools and libraries

See [Qtrac website](https://www.qtrac.eu/sitemap.html) for these and other tools and libraries.
