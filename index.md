In addition to FOSS I have commercial PDF comparison products, in particular:
- [DiffPDF for Windows](https://www.qtrac.eu/diffpdf.html) an easy-to-use GUI application, and
- [comparepdfcmd for Windows](https://www.qtrac.eu/comparepdfcmd.html) a command line/console tool ideal for scripting and testing use.

### Gravitate Game

A SameGame/TileFall-like game written in [Rust/FLTK](https://github.com/mark-summerfield/gravitate-rs).
I have created versions of this game in many different languages using various GUI libraries, but the Rust/FLTK one is by far the best.
The repo includes a 1.9MB Windows binary (64-bit).
The source can be used to build on Linux and on Windows (32- or 64-bit).

### AMP 
[“Another Music Player”](https://github.com/mark-summerfield/amp-rs)
This provides a basic but useful example of Rust/FLTK andthe Soloud sound library.
It should be especially handy for audio books since at startup it restores
the last played track at the exact position it had reached.
The repo includes a 2.5MB Windows binary (64-bit).
The source can be used to build on Linux and on Windows (32- or 64-bit).

### CharFind
[CharFind](https://github.com/mark-summerfield/charfind) is an application for finding Unicode characters.
The repo includes a 1.9MB Windows binary (64-bit).
The source can be used to build on Linux and on Windows (32- or 64-bit).

### XindeX

[XindeX](https://github.com/mark-summerfield/xindex) is an easy to learn and use GUI application for creating, editing, and outputting indexes (e.g., for books).

This has been tested on Windows and Linux and is written in Python 3 (>=3.6) using PySide 1 (Qt 4.8).

### Retest

[Retest](https://www.qtrac.eu/retest.html) is an easy to use application (and Rust library) for automating black box regression testing on Windows and Unix.
([Windows 64-bit binary 905KB .zip](https://www.qtrac.eu/retest-4.0.6.zip).)

### Diff Libraries

The Python standard library includes the `difflib` module which has an excellent sequence matcher to find and report the differences between two sequences (e.g., between two sequences of lines). I've ported a version of this functionality to
[D as `ddiff`](https://github.com/mark-summerfield/ddiff),
[Nim as `diff`](https://github.com/mark-summerfield/diff), and
[Rust as `Differ`](https://github.com/mark-summerfield/differ). Only the Rust version is (passively) maintained.
