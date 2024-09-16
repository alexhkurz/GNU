 # History of GNU

WARNING: This literature review has been curated with the help of an LLM through the [Cursor AI](https://www.cursor.com/) interfaceand not been independently verified yet.

The GNU Project was launched by Richard Stallman on September 27, 1983, to create a free Unix-likeoperating system. GNU is a recursive acronym for
"GNU's Not Unix!".
## Widely Used GNU Utilities and Programs

- **GNU Bash**: The Bourne Again Shell, a widely used command processor.
  - **Author**: Brian Fox
  - **Initial Release**: 1989
- **GNU Core Utilities**: Basic file, shell, and text manipulation utilities.
  - **Author**: David MacKenzie
  - **Initial Release**: 1992
- **GNU Compiler Collection (GCC)**: A compiler system supporting various programming languages.
  - **Author**: Richard Stallman
  - **Initial Release**: 1987
- **GNU Emacs**: An extensible, customizable text editor.
  - **Author**: Richard Stallman
  - **Initial Release**: 1985
- **GNU Make**: A build automation tool.
  - **Author**: Richard Stallman
  - **Initial Release**: 1988
- **GNU Debugger (GDB)**: A portable debugger.
  - **Author**: Richard Stallman
  - **Initial Release**: 1986
- **GNU Binutils**: A collection of binary tools.
  - **Author**: Steve Chamberlain
  - **Initial Release**: 1990
- **GNU Wget**: A network downloader.
  - **Author**: Hrvoje Nikšić
  - **Initial Release**: 1996
- **GNU Tar**: An archiving utility.
  - **Author**: John Gilmore
  - **Initial Release**: 1988
- **GNU Sed**: A stream editor for filtering and transforming text.
  - **Author**: Lee E. McMahon
  - **Initial Release**: 1974 (as part of Unix), adopted by GNU in the 1980s

 ## History of GNU Core Utilities

 The GNU Core Utilities, or coreutils, is a package of GNU software containing reimplementations of many basic Unix tools. It was created to provide a
 consistent and free set of tools for Unix-like operating systems. The coreutils package combines three formerly separate packages: fileutils, shellutil
 and textutils.

 ### Most Popular Command-Line Tools

- **[ls](https://en.wikipedia.org/wiki/Ls), [cp](https://en.wikipedia.org/wiki/Cp_(Unix)), [mv](https://en.wikipedia.org/wiki/Mv), [rm](https://en.wikipedia.org/wiki/Rm_(Unix)), [chmod](https://en.wikipedia.org/wiki/Chmod), [chown](https://en.wikipedia.org/wiki/Chown), [cat](https://en.wikipedia.org/wiki/Cat_(Unix)), [echo](https://en.wikipedia.org/wiki/Echo_(command))**:
  - **Original Unix Author**: Ken Thompson
  - **Original Unix Release**: circa 1971-1973
  - **GNU Implementation**: Richard Stallman
  - **GNU Initial Release**: 1980s (exact dates vary)
  - **Included in GNU Coreutils**: 1992

- **[touch](https://en.wikipedia.org/wiki/Touch_(command))**:
  - **Original Unix Author**: Unknown (part of early Unix)
  - **Original Unix Release**: 1970s
  - **GNU Implementation**: Richard Stallman
  - **GNU Initial Release**: 1980s
  - **Included in GNU Coreutils**: 1992

- **[date](https://en.wikipedia.org/wiki/Date_(Unix)), [head](https://en.wikipedia.org/wiki/Head_(Unix)), [tail](https://en.wikipedia.org/wiki/Tail_(Unix))**:
  - **Original Unix Author**: Unknown (part of early Unix)
  - **Original Unix Release**: 1970s
  - **GNU Implementation**: David MacKenzie
  - **GNU Initial Release**: 1980s
  - **Included in GNU Coreutils**: 1992

- **[grep](https://en.wikipedia.org/wiki/Grep)**:
  - **Original Unix Author**: Ken Thompson
  - **Original Unix Release**: 1974
  - **GNU Implementation**: Mike Haertel
  - **GNU Initial Release**: 1988
  - **Included in GNU Coreutils**: 1992

- **[awk](https://en.wikipedia.org/wiki/AWK)**:
  - **Original Unix Authors**: Alfred Aho, Peter Weinberger, and Brian Kernighan
  - **Original Unix Release**: 1977
  - **GNU Implementation**: Paul Rubin, Jay Fenlason, Richard Stallman
  - **GNU Initial Release**: 1988 (as gawk)
  - **Note**: Not part of GNU Coreutils, but a separate GNU package

- **[find](https://en.wikipedia.org/wiki/Find_(Unix))**:
  - **Original Unix Author**: Unknown (part of early Unix)
  - **Original Unix Release**: 1970s
  - **GNU Implementation**: Eric B. Decker, James Youngman, and others
  - **GNU Initial Release**: 1990
  - **Note**: Part of GNU Findutils, not Coreutils

 // ... (other tools follow a similar pattern)

## State of the Art Before GNU

Before Richard Stallman launched the GNU Project in 1983, the computing landscape was quite different:

- **Proprietary Unix Systems**: Unix was widely used in academic and commercial settings, but it was proprietary software owned by AT&T.
  - Various Unix versions existed, such as BSD (Berkeley Software Distribution), but they still contained AT&T code.
  - Commercial Unix systems were expensive and came with restrictive licenses.

- **Lack of Free Software**: Most software was proprietary, and users didn't have the freedom to study, modify, or share the source code.

- **Emerging Personal Computer Market**: PCs were becoming popular, but most ran proprietary operating systems like MS-DOS[^1].

- **Limited Collaboration**: The closed nature of software hindered collaboration and innovation among programmers.

[^1]: MS-DOS was first released in 1981, just two years before the GNU Project began. The IBM PC, which popularized the personal computer market, was introduced in 1981 as well. Prior to MS-DOS, early personal computers used a variety of operating systems, including CP/M and Apple DOS. The rapid adoption of the IBM PC and MS-DOS in the early 1980s was part of the changing landscape that motivated Stallman to start the GNU Project.

### The Problem Stallman Set Out to Solve

Stallman's primary goal was to create a completely free Unix-like operating system. He aimed to:

1. Provide users with the freedom to run, copy, distribute, study, change, and improve software.
2. Foster a community of collaborative development and sharing.
3. Ensure that users could control their computing, rather than being controlled by proprietary software vendors.
4. Create high-quality, free alternatives to common Unix utilities and tools.

By launching GNU, Stallman sought to build a complete operating system that respected users' freedoms, which he saw as increasingly threatened by the proprietary software model.
