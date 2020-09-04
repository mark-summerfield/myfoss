In addition to FOSS I also have commecial PDF comparison products, [DiffPDF for Windows](https://www.qtrac.eu/diffpdf.html) an easy-to-use GUI application, and [comparepdfcmd for Windows](https://www.qtrac.eu/comparepdfcmd.html) a command line/console tool ideal for scripting and testing use.

### Gravitate Game

A SameGame/TileFall-like game.

[Windows 64-bit binary 3.5MB .zip](https://github.com/mark-summerfield/gravitate-wx/blob/master/Gravitate.zip).

The Windows binary is for the
[C++/wxWidgets *(newest and best version)*](https://github.com/mark-summerfield/gravitate-wx).
However, I've also done versions using:
[D/GtkD](https://github.com/mark-summerfield/gravitate-d),
Java/Swing,
[Nim/NiGui](https://github.com/mark-summerfield/gravitate-nim),
Python/Tkinter,
Python/wxPython,
and JavaScript.
All the versions without github links can be downloaded from [Qtrac](http://www.qtrac.eu/gravitate.html).

### XindeX

[XindeX](https://github.com/mark-summerfield/xindex) is an easy to learn and use GUI application for creating, editing, and outputting indexes (e.g., for books).

This has been tested on Windows and Linux and is written in Python 3 (>=3.6) using PySide 1 (Qt 4.8).

### Retest

[Retest](https://www.qtrac.eu/retest.html) is an easy to use application (and Rust library) for automating black box regression testing on Windows and Unix.

[Windows 64-bit binary 3.5MB .zip](https://www.qtrac.eu/retest-4.0.6.zip).

### Diff Libraries

The Python standard library includes the `difflib` module which has an excellent sequence matcher to find and report the differences between two sequences (e.g., between two sequences of lines). I've ported a version of this functionality to
[D as `ddiff`](https://github.com/mark-summerfield/ddiff),
[Nim as `diff`](https://github.com/mark-summerfield/diff), and
[Rust as `Differ`](https://github.com/mark-summerfield/differ).
