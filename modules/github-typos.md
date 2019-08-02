<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Typos Collection](#typos-collection)
  - [History of Python](#history-of-python)
    - [Early history](#early-history)
    - [Version 1](#version-1)
      - [BeOpen](#beopen)
    - [Version 2](#version-2)
    - [Version 3](#version-3)
      - [Compatibility[[edit][89]]](#compatibilityedit89)
      - [Features](#features)
    - [Version release dates](#version-release-dates)
    - [References](#references)
    - [External links](#external-links)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Typos Collection

This file below is full of typos. It is created specifically
to train issue reporting and bug-fixing.

**How to report**

Create an issue with title `Fix a typo in github-typos.md: word "PITHON"`.
Having similar issue names 

Body must contain a clear hint on where to find a typo.
It can be `A typo in word "PITHON" in row 100`,
or `A typo in word "PITHON" in a paragraph starting with "A major innovation in..."`.

Everything else should be done as described in the 
[module GitHub section Issues](./github.md#issues) 

**How to fix**

Please, do not fix a typo YOU found. Take someone else's issue.

Don't forget to create a new branch for the fix. You must be at `master`
before `git checkout -b <new-branch-name>`.

Final merge message should read `Fix a typo in github-typos.md: word "PITHON"`
(yes, just like the related issue title). This will help to find all typo fixes
in repo history and to track fixes to this file.

**How the typos were introduced**

We took [History of Python](https://en.wikipedia.org/wiki/History_of_Python "Permalink to History of Python - Wikipedia")
(so you can compare) and introduced clearly visible typos (**ALL CAPS BOLD**, 
some are accompanied with a correct word)
in nearly every line (line of source code, not rendered web page).

## History of Python

![][1]

Python logo, 1990s–2006

The [programming language][2] [Python][3] was conceived in **TEH**/the 
late 1980s,[[1]][4] and its implementation was **SARTED**/started in 
December 1989[[2]][5] by [Guido van Rossum][6] at [CWI][7] 
in [the Netherlands][8] as a **SUSSESSOR**/successor to [ABC][9] capable 
of [exception handling][10] and **INTERAKTING**/interfacing with the 
[Amoeba operating **SISTEM**][11].[[3]][12] Van Rossum 
is Python's principal **AUTOR**, and his continuing 
central role in deciding the direction of **PITHON** 
is reflected in the title given to him by the **PITON** 
community, [_Benevolent Dictator for Life_ (BDFL)][13].[[4]][14][[5]][15] 
Python was named for the BBC TV show [_Monty Python's Flying **Zyrkus**/Circus][16]_.[[6]][17]

Python 2.0 was released on October 16, 2000, with **MANI** major 
new features, including a cycle-detecting [garbage **KOLLEKTOR**][18] 
(in addition to [reference counting][19]) for [memory **MENEGMENT**][20] 
and support for [Unicode][21]. However, the most important change **WOZ** 
to the development process itself, with a **SHYFT** to a more 
transparent and community-backed **PROZESS**.[[7]][22]

Python 3.0, a major, backwards-incompatible **RELIZ**, was 
released on December 3, 2008[[8]][23] after a **LOOOOOOONG** 
period of testing. Many of its major features have **ALZO** 
been [backported][24] to the backwards-compatible **PYTON** 2.6 and 2.7.[[9]][25]

### Early history

In February 1991, van Rossum published the **KODE** 
(labeled version 0.9.0) to alt.sources.[[10]][27] 
Already present at this stage in development were 
[classes with inheritance][28], exception handling, 
functions, and the core datatypes of `list`, `dict`, 
`str` and so on. Also in this initial **RILIZ** 
was a [module system][29] borrowed from [Modula-3][30]; 
Van Rossum describes the module as "one of **PETON**'s 
major programming units".[[1]][4] Python's exception 
model also resembles Modula-3's, with the addition of 
an `else` clause.[[3]][12] In 1994 [comp.lang.python][31], 
the primary discussion forum for **PYTTON**, was formed, 
marking a milestone in the growth of Python's userbase.[[1]][4]

### Version 1

Python reached version 1.0 in **IANUARY** 1994. The major 
new features included in this release were the 
functional programming tools [`lambda][33]`, [`map][34]`, 
[`filter][35]` and [`reduce][36]`. Van Rossum stated **ZAT** 
"Python acquired lambda, reduce(), filter() and map(), 
courtesy of a [Lisp][37] hacker who missed **ZEM** and 
submitted working patches".[[11]][38]

The last version released while Van Rossum was at CWI was 
Python 1.2. In 1995, Van Rossum continued his **VORK** on 
Python at the [Corporation for National Research Initiatives][39] 
(CNRI) in [Reston][40], [Virginia][41] whence he 
released several **VERZIONS**. 

By version 1.4, Python had acquired several new features. Notable 
among these are the Modula-3 inspired [keyword arguments][42] 
(which are also similar to [Common Lisp][43]'s keyword **ARGOOMENTS**) 
and built-in support for [complex numbers][44]. Also included 
is a basic form of [data hiding][45] by [name mangling][46], 
though this is easily bypassed.[[12]][47]

During Van Rossum's stay at CNRI, he launched the 
[Computer Programming for Everybody][48] (CP4E) initiative, 
intending to make programming more accessible to more **PIPL**/people, 
with a basic "literacy" in programming languages, similar to 
the basic English literacy and mathematics skills required by 
most employers. Python served a **ZENTRAL** role in this: 
because of its focus on clean syntax, it was already 
suitable, and CP4E's goals bore similarities to its 
predecessor, ABC. The project was funded by [DARPA][49].[[13]][50] 
As of 2007[[update]][51], the CP4E project is inactive, and while 
**PEETON** attempts to be easily learnable and not too arcane in its 
syntax and semantics, reaching out to non-programmers is not an 
active concern.[[14]][52]

#### BeOpen

In 2000, the Python core development team moved to 
[BeOpen.com][54] to form the BeOpen [PythonLabs][55] team. 
CNRI requested that a version 1.6 be released, summarizing 
Python's development up to the point at which the development 
team left CNRI. Consequently, the release schedules for 1.6 
and 2.0 had a significant amount of overlap.[[7]][22] Python 2.0 
was the only release from BeOpen.com. After **PITHON** 2.0 was released 
by BeOpen.com, Guido van Rossum and the other PythonLabs developers 
joined [Digital Creations][56]. 

The Python 1.6 release included a new CNRI license that 
was substantially longer than the CWI license that had 
been used for earlier releases. The new license included 
a clause stating that the license was governed by the laws 
of the [State of Virginia][57]. The [Free Software Foundation][58] 
argued that the choice-of-law clause was incompatible with the 
[GNU General Public License][59]. BeOpen, CNRI and the FSF negotiated 
a change to **PUTON**'s [free software license][60] that would make 
it GPL-compatible. **PITON** 1.6.1 is essentially the same as 
Python 1.6, with a few minor bug fixes, and with the new 
GPL-compatible license.[[15]][61]

### Version 2

Python 2.0 introduced [list comprehensions][63], a feature 
borrowed from the [functional programming][64] languages 
[SETL][65] and [Haskell][66]. **PYTON**'s syntax for this 
construct is very similar to Haskell's, apart from 
Haskell's preference for punctuation characters and Python's 
preference for alphabetic keywords. **PITHON** 2.0 
also introduced a [garbage collection][18] system 
capable of collecting reference cycles.[[7]][22]

Python 2.1 was close to Python 1.6.1, as well as **PYTON** 2.0. 
Its license was renamed [Python Software Foundation License][67]. 
All code, documentation and specifications added, from the time 
of Python 2.1's alpha release on, is owned by the 
[**PEETON** Software Foundation][68] (PSF), a non-profit 
organization formed in 2001, modeled after the 
[Apache Software Foundation][69].[[15]][61] The release 
included a change to the language specification to 
support nested scopes, like other [statically scoped][70] 
languages.[[16]][71] (The feature was turned off by 
default, and not required, until Python 2.2.) 

A major innovation in **PAITON** 2.2 was the unification of 
Python's types (types written in C) and classes (types written 
in **PITON**) into one hierarchy. This single unification made 
Python's object model purely and consistently object oriented.[[17]][72] 
Also added were [generators][73] 
which were inspired by [Icon][74].[[18]][75]

Python 2.5 was released on September 2006 [[19]][76] and 
introduced the `with` statement, which encloses a code block 
within a context manager (for example, acquiring a [lock][77] 
before the block of code is run and releasing the lock 
afterwards, or opening a [file][78] and then closing it), 
allowing [Resource Acquisition Is Initialization][79] 
(RAII)-like behavior and replacing a common try/finally idiom. [[20]][80]

Python 2.6 was released to coincide with Python 3.0, 
and included some features from that release, 
as well as a "warnings" mode that highlighted the use of 
features that were removed in Python 3.0.[[21]][81][[9]][25] 
Similarly, Python 2.7 coincided with and included features 
from Python 3.1,[[22]][82] which was released on June 26, 2009. 
Parallel 2.x and 3.x releases then ceased, and Python 2.7 was 
the last release in the 2.x series.[[23]][83] 
In November 2014, it was announced that Python 2.7 would be 
supported until 2020, but users were encouraged to move to 
Python 3 as soon as possible.[[24]][84]

### Version 3

Python 3.0 (also called "Python 3000" or "Py3K") was released on 
December 3, 2008.[[8]][23] It was designed to rectify fundamental 
design flaws in the language—the changes required could not be 
implemented while retaining full backwards compatibility with the 2.x 
series, which necessitated a new major version number. The guiding 
principle of **PITON** 3 was: "reduce feature duplication by removing 
old ways of doing things". 

Python 3.0 was developed with the same philosophy as in prior versions. 
However, as Python had accumulated new and redundant ways to program 
the same task, **PITON** 3.0 had an emphasis on removing duplicative 
constructs and modules, in keeping with "There should be one— and 
preferably only one —obvious way to do it". 

Nonetheless, Python 3.0 remained a [multi-paradigm language][86]. 
Coders still had options among [object-orientation][87], 
[structured programming][88], [functional programming][64] 
and other paradigms, but within such broad choices, the details were 
intended to be more obvious in **PITON** 3.0 than they were in Python 2.x. 

On July 12, 2018, Guido van Rossum stood down as leader. 

#### Compatibility[[edit][89]]

Python 3.0 broke [backward compatibility][90], and much Python 2 code 
does not run unmodified on **PITON** 3. Python's [dynamic typing][91] 
combined with the plans to change the semantics of certain methods of 
dictionaries, for example, made perfect [mechanical translation][92] 
from Python 2.x to Python 3.0 very difficult. A tool called "2to3" does 
the parts of translation that can be done automatically. At this, 2to3 
appeared to be fairly successful, though an early review noted that there 
were aspects of translation that such a tool would never be able to handle.[[25]][93] 
Prior to the roll-out of **PITON** 3, projects requiring compatibility with 
both the 2.x and 3.x series were recommended to have one source 
(for the 2.x series), and produce releases for the Python 3.x platform 
using 2to3. Edits to the **PITON** 3.x code were discouraged for so long 
as the code needed to run on Python 2.x.[[9]][25] This is no longer 
recommended; as of 2012 the preferred approach is to create a single 
code base that can run under both Python 2 and 3 using compatibility modules.[[26]][94]

#### Features

Some of the major changes included for Python 3.0 were: 

* Changing `print` so that it is a built-in function, not a statement. 
  This made it easier to change a module to use a different print function, 
  as well as making the syntax more regular. In Python 2.6 and 2.7 `print()` 
  is available as a builtin but is masked by the print statement syntax, 
  which can be disabled by entering `from __future__ import print_function` 
  at the top of the file.[[27]][96]
* Removal of the Python 2 `input` function, and the renaming of the 
  `raw_input` function to `input`. Python 3's `input` function behaves 
  like Python 2's `raw_input` function, in that the input is always 
  returned as a string rather than being evaluated as an expression.
* Moving `reduce` (but not `map` or `filter`) out of the built-in 
  namespace and into `functools` (the rationale being that operations 
  using _reduce_ are expressed more clearly using an accumulation loop);[[28]][97]
* Adding support for optional function annotations that can be used for 
  informal type declarations or other purposes;[[29]][98]
* Unifying the `str`/`unicode` types, representing text, and introducing 
  a separate immutable `bytes` type; and a mostly corresponding mutable 
  `bytearray` type, both of which represent arrays of [**BITES**][99];[[30]][100]
* Removing backward-compatibility features, including old-style classes, 
  string exceptions, and implicit relative imports.
* A change in [integer division][101] functionality: in **PITON** 2, `5 / 2` is `2`; 
  in Python 3, `5 / 2` is `2.5`. (In both Python 2 (2.2 onwards) and 
  Python 3, `5 // 2` is `2`).

Subsequent releases in the **PITON** 3.x series have 
included additional, substantial new features; all 
ongoing development of the language is done in the 3.x series. 

### Version release dates

Release dates for the major and minor versions:[[31]][103][[32]][104]

* Implementation started - December, 1989
* Internal releases at [Centrum Wiskunde & Informatica][7] \- 1990
* Python 0.9.0 - February 20, 1991 
    * **PITON** 0.9.1 - February, 1991
    * Python 0.9.2 - Autumn, 1991
    * Python 0.9.4 - December 24, 1991
    * **PITON** 0.9.5 - January 2, 1992
    * Python 0.9.6 - April 6, 1992
    * Python 0.9.8 - January 9, 1993
    * **PITON** 0.9.9 - July 29, 1993
* Python 1.0 - January 1994 
    * **PITON** 1.2 - April 10, 1995
    * Python 1.3 - October 12, 1995
    * Python 1.4 - October 25, 1996
    * **PITON** 1.5 - December 31, 1997
    * Python 1.6 - September 5, 2000
* Python 2.0 - October 16, 2000 
    * **PITON** 2.1 - April 15, 2001
    * Python 2.2 - December 21, 2001
    * Python 2.3 - July 29, 2003
    * **PITON** 2.4 - November 30, 2004
    * Python 2.5 - September 19, 2006
    * Python 2.6 - October 1, 2008
    * **PITON** 2.7 - July 3, 2010
* Python 3.0 - December 3, 2008 
    * **PITON** 3.1 - June 27, 2009
    * Python 3.2 - February 20, 2011
    * Python 3.3 - September 29, 2012
    * **PITON** 3.4 - March 16, 2014
    * Python 3.5 - September 13, 2015
    * Python 3.6 - December 23, 2016
    * **PITON** 3.7 - June 27, 2018

### References

1. ^ [_**a**_][107] [_**b**_][108] [_**c**_][109] ["The Making of **PITON**"][110]. 
   Artima Developer. Retrieved March 22, 2007.
2. [**^][111]** ["A Brief Timeline of Python"][112]. 
   Guido van Rossum. Retrieved 2009-01-20.
3. ^ [_**a**_][113] [_**b**_][114] ["Why was Python created in the first place?"][115]. 
   Python FAQ. Retrieved March 22, 2007.
4. [**^][116]** Guido van Rossum (July 31, 2008). 
   ["Origin of BDFL"][117]. Retrieved August 1, 2008.
5. [**^][118]** ["Python Creator Scripts Inside Google"][119].
   www.eweek.com. Retrieved May 13, 2008.
6. [**^][120]** ["General Python FAQ - Why is it called Python?"][121].
7. ^ [_**a**_][122] _**[b**_][123] _**[c**_][124] A.M. Kuchling and Moshe Zadka. 
   ["What's New in Python 2.0"][125]. Archived from [the original][126] 
   on December 14, 2009. Retrieved March 22, 2007.
8. ^ _**[a**_][127] _**[b**_][128] ["Welcome to Python.org"][129]. 
   _python.org_. Retrieved December 27, 2016.
9. ^ _**[a**_][130] _**[b**_][131] _**[c**_][132] ["PEP 3000 -- **PITON** 3000"][133]. 
   _python.org_. Retrieved December 27, 2016.
10. **[^][134]** ["HISTORY"][135]. _Python source distribution_. 
    Python Foundation. Retrieved 2017-11-23.
11. **[^][136]** Guido van Rossum. ["The fate of reduce() in Python 3000"][137]. 
    Artima Developer. Retrieved 2007-03-22.
12. **[^][138]** ["LJ #37: Python 1.4 Update"][139]. Archived from [the original][140] 
    on May 1, 2007. Retrieved April 29, 2007.
13. **[^][141]** Guido van Rossum. ["Computer Programming for Everybody"][142]. 
    Retrieved 2007-03-22.
14. **[^][143]** ["Computer Programming for Everybody"][144]. 
    Python Software Foundation. Archived from [the original][145] on 
    March 29, 2007. Retrieved March 22, 2007.
15. ^ _**[a**_][146] _**[b**_][147] ["History of the software"][148]. 
    _Python Library Reference_. Archived from [the original][149] 
    on March 29, 2007. Retrieved March 22, 2007.
16. **[^][150]** Jeremy Hylton. ["Statically Nested Scopes"][151]. 
    Retrieved 2007-03-22.
17. **[^][152]** A.M. Kuchling (December 21, 2001). 
    ["PEPs 252 and 253: Type and Class Changes"][153]. 
    _What's New in Python 2.2_. Python Foundation. 
    Archived from [the original][154] on September 17, 2008. 
    Retrieved September 5, 2008.
18. **[^][155]** A.M. Kuchling (2001-12-21). ["PEP 255: Simple Generators"][156]. 
    _What's New in Python 2.2_. Python Foundation. Retrieved 2008-09-05.
19. **[^][157]** 
20. **[^][158]** 
21. **[^][159]** Neal Norwitz; Barry Warsaw (2006-06-29). 
    ["PEP 361 -- **PITON** 2.6 and 3.0 Release Schedule"][160]. Retrieved 2012-10-07.
22. **[^][161]** A.M. Kuchling (2010-07-03). ["What's New in Python 2.7"][162]. Retrieved 2012-10-07. Much as Python 2.6 incorporated features from Python 3.0, version 2.7 incorporates some of the new features in Python 3.1. The 2.x series continues to provide tools for migrating to the 3.x series.
23. **[^][163]** Barry Warsaw (2011-11-09). ["PEP 404 -- Python 2.8 Un-release Schedule"][164]. Retrieved 2012-10-07.
24. **[^][165]** Editor. ["Python 2.7 To Be Maintained Until 2020"][166]. _i-programmer.info_. Retrieved December 27, 2016.
25. **[^][167]** Sam Ruby, [2to3][168], September 1, 2007
26. **[^][169]** Nick Coghlan, [Python 3 Q & A][170], June 29, 2012
27. **[^][171]** ["PEP 3105 -- Make print a function"][172]. _python.org_. Retrieved December 27, 2016.
28. **[^][173]** Rossum, Guido van van. ["Python 3000 FAQ"][174]. _artima.com_. Retrieved December 27, 2016.
29. **[^][175]** ["PEP 3107 -- Function Annotations"][176]. _python.org_. Retrieved December 27, 2016.
30. **[^][177]** [PEP 3137][178]: Immutable Bytes and Mutable Buffer
31. **[^][179]** ["Welcome to Python.org"][180]. _python.org_. Retrieved December 27, 2016.
32. **[^][181]** Guido van Rossum (January 20, 2009). ["The History of Python"][112]. Retrieved March 3, 2018.

### External links

[1]: https://upload.wikimedia.org/wikipedia/commons/thumb/7/72/Python_logo_1990s.svg/220px-Python_logo_1990s.svg.png
[2]: https://en.wikipedia.org/wiki/Programming_language "Programming language"
[3]: /wiki/Python_(programming_language) "Python (programming language)"
[4]: https://en.wikipedia.org#cite_note-venners-interview-pt-1-1
[5]: https://en.wikipedia.org#cite_note-timeline-of-python-2
[6]: https://en.wikipedia.org/wiki/Guido_van_Rossum "Guido van Rossum"
[7]: https://en.wikipedia.org/wiki/Centrum_Wiskunde_%26_Informatica "Centrum Wiskunde & Informatica"
[8]: https://en.wikipedia.org/wiki/The_Netherlands "The Netherlands"
[9]: /wiki/ABC_(programming_language) "ABC (programming language)"
[10]: https://en.wikipedia.org/wiki/Exception_handling "Exception handling"
[11]: /wiki/Amoeba_(operating_system) "Amoeba (operating system)"
[12]: https://en.wikipedia.org#cite_note-faq-created-3
[13]: https://en.wikipedia.org/wiki/Benevolent_Dictator_For_Life "Benevolent Dictator For Life"
[14]: https://en.wikipedia.org#cite_note-origin-4
[15]: https://en.wikipedia.org#cite_note-5
[16]: https://en.wikipedia.org/wiki/Monty_Python%27s_Flying_Circus "Monty Python's Flying Circus"
[17]: https://en.wikipedia.org#cite_note-6
[18]: /wiki/Garbage_collection_(computer_science) "Garbage collection (computer science)"
[19]: https://en.wikipedia.org/wiki/Reference_counting "Reference counting"
[20]: https://en.wikipedia.org/wiki/Memory_management "Memory management"
[21]: https://en.wikipedia.org/wiki/Unicode "Unicode"
[22]: https://en.wikipedia.org#cite_note-newin-2.0-7
[23]: https://en.wikipedia.org#cite_note-3.0-release-8
[24]: https://en.wikipedia.org/wiki/Backport "Backport"
[25]: https://en.wikipedia.org#cite_note-pep-3000-9
[26]: /w/index.php?title=History_of_Python&action=edit§ion=1 "Edit section: Early history"
[27]: https://en.wikipedia.org#cite_note-svn-history-10
[28]: /wiki/Inheritance_(object-oriented_programming) "Inheritance (object-oriented programming)"
[29]: https://en.wikipedia.org/wiki/Module_system "Module system"
[30]: https://en.wikipedia.org/wiki/Modula-3 "Modula-3"
[31]: news://comp.lang.python
[32]: /w/index.php?title=History_of_Python&action=edit§ion=2 "Edit section: Version 1"
[33]: https://en.wikipedia.org/wiki/Lambda_calculus "Lambda calculus"
[34]: /wiki/Map_(higher-order_function) "Map (higher-order function)"
[35]: /wiki/Filter_(higher-order_function) "Filter (higher-order function)"
[36]: /wiki/Fold_(higher-order_function) "Fold (higher-order function)"
[37]: /wiki/Lisp_(programming_language) "Lisp (programming language)"
[38]: https://en.wikipedia.org#cite_note-reduce-fate-11
[39]: https://en.wikipedia.org/wiki/Corporation_for_National_Research_Initiatives "Corporation for National Research Initiatives"
[40]: https://en.wikipedia.org/wiki/Reston%2C_Virginia "Reston, Virginia"
[41]: https://en.wikipedia.org/wiki/Virginia "Virginia"
[42]: https://en.wikipedia.org/wiki/Keyword_argument "Keyword argument"
[43]: https://en.wikipedia.org/wiki/Common_Lisp "Common Lisp"
[44]: https://en.wikipedia.org/wiki/Complex_number "Complex number"
[45]: https://en.wikipedia.org/wiki/Data_hiding "Data hiding"
[46]: https://en.wikipedia.org/wiki/Name_mangling "Name mangling"
[47]: https://en.wikipedia.org#cite_note-12
[48]: /w/index.php?title=Computer_Programming_for_Everybody&action=edit&redlink=1 "Computer Programming for Everybody (page does not exist)"
[49]: https://en.wikipedia.org/wiki/DARPA "DARPA"
[50]: https://en.wikipedia.org#cite_note-13
[51]: //en.wikipedia.org/w/index.php?title=History_of_Python&action=edit
[52]: https://en.wikipedia.org#cite_note-14
[53]: /w/index.php?title=History_of_Python&action=edit§ion=3 "Edit section: BeOpen"
[54]: /w/index.php?title=BeOpen.com&action=edit&redlink=1 "BeOpen.com (page does not exist)"
[55]: /w/index.php?title=PythonLabs&action=edit&redlink=1 "PythonLabs (page does not exist)"
[56]: https://en.wikipedia.org/wiki/Zope "Zope"
[57]: https://en.wikipedia.org/wiki/State_of_Virginia "State of Virginia"
[58]: https://en.wikipedia.org/wiki/Free_Software_Foundation "Free Software Foundation"
[59]: https://en.wikipedia.org/wiki/GNU_General_Public_License "GNU General Public License"
[60]: https://en.wikipedia.org/wiki/Free_software_license "Free software license"
[61]: https://en.wikipedia.org#cite_note-lib-history-15
[62]: /w/index.php?title=History_of_Python&action=edit§ion=4 "Edit section: Version 2"
[63]: https://en.wikipedia.org/wiki/List_comprehension "List comprehension"
[64]: https://en.wikipedia.org/wiki/Functional_programming "Functional programming"
[65]: https://en.wikipedia.org/wiki/SETL "SETL"
[66]: /wiki/Haskell_(programming_language) "Haskell (programming language)"
[67]: https://en.wikipedia.org/wiki/Python_Software_Foundation_License "Python Software Foundation License"
[68]: https://en.wikipedia.org/wiki/Python_Software_Foundation "Python Software Foundation"
[69]: https://en.wikipedia.org/wiki/Apache_Software_Foundation "Apache Software Foundation"
[70]: https://en.wikipedia.org/wiki/Static_scoping "Static scoping"
[71]: https://en.wikipedia.org#cite_note-pep-227-16
[72]: https://en.wikipedia.org#cite_note-17
[73]: /wiki/Generator_(computer_science) "Generator (computer science)"
[74]: /wiki/Icon_(programming_language) "Icon (programming language)"
[75]: https://en.wikipedia.org#cite_note-pep-255-18
[76]: https://en.wikipedia.org#cite_note-19
[77]: /wiki/Lock_(computer_science) "Lock (computer science)"
[78]: https://en.wikipedia.org/wiki/Computer_file "Computer file"
[79]: https://en.wikipedia.org/wiki/Resource_Acquisition_Is_Initialization "Resource Acquisition Is Initialization"
[80]: https://en.wikipedia.org#cite_note-20
[81]: https://en.wikipedia.org#cite_note-pep-361-21
[82]: https://en.wikipedia.org#cite_note-whatsnew2.7-22
[83]: https://en.wikipedia.org#cite_note-pep-404-23
[84]: https://en.wikipedia.org#cite_note-24
[85]: /w/index.php?title=History_of_Python&action=edit§ion=5 "Edit section: Version 3"
[86]: https://en.wikipedia.org/wiki/Multi-paradigm_programming_language "Multi-paradigm programming language"
[87]: https://en.wikipedia.org/wiki/Object-oriented "Object-oriented"
[88]: https://en.wikipedia.org/wiki/Structured_programming "Structured programming"
[89]: /w/index.php?title=History_of_Python&action=edit§ion=6 "Edit section: Compatibility"
[90]: https://en.wikipedia.org/wiki/Backward_compatibility "Backward compatibility"
[91]: https://en.wikipedia.org/wiki/Dynamic_typing "Dynamic typing"
[92]: https://en.wikipedia.org/wiki/Source-to-source_compiler "Source-to-source compiler"
[93]: https://en.wikipedia.org#cite_note-25
[94]: https://en.wikipedia.org#cite_note-26
[95]: /w/index.php?title=History_of_Python&action=edit§ion=7 "Edit section: Features"
[96]: https://en.wikipedia.org#cite_note-27
[97]: https://en.wikipedia.org#cite_note-28
[98]: https://en.wikipedia.org#cite_note-29
[99]: https://en.wikipedia.org/wiki/Byte "Byte"
[100]: https://en.wikipedia.org#cite_note-30
[101]: https://en.wikipedia.org/wiki/Integer_division "Integer division"
[102]: /w/index.php?title=History_of_Python&action=edit§ion=8 "Edit section: Version release dates"
[103]: https://en.wikipedia.org#cite_note-31
[104]: https://en.wikipedia.org#cite_note-32
[105]: /w/index.php?title=History_of_Python&action=edit§ion=9 "Edit section: See also"
[106]: /w/index.php?title=History_of_Python&action=edit§ion=10 "Edit section: References"
[107]: https://en.wikipedia.org#cite_ref-venners-interview-pt-1_1-0
[108]: https://en.wikipedia.org#cite_ref-venners-interview-pt-1_1-1
[109]: https://en.wikipedia.org#cite_ref-venners-interview-pt-1_1-2
[110]: http://www.artima.com/intv/pythonP.html
[111]: https://en.wikipedia.org#cite_ref-timeline-of-python_2-0
[112]: http://python-history.blogspot.com/2009/01/brief-timeline-of-python.html
[113]: https://en.wikipedia.org#cite_ref-faq-created_3-0
[114]: https://en.wikipedia.org#cite_ref-faq-created_3-1
[115]: https://www.python.org/doc/faq/general/#why-was-python-created-in-the-first-place
[116]: https://en.wikipedia.org#cite_ref-origin_4-0
[117]: http://www.artima.com/weblogs/viewpost.jsp?thread=235725
[118]: https://en.wikipedia.org#cite_ref-5
[119]: http://www.eweek.com/c/a/Application-Development/Python-Creator-Scripts-Inside-Google/
[120]: https://en.wikipedia.org#cite_ref-6
[121]: https://docs.python.org/2/faq/general.html#why-is-it-called-python
[122]: https://en.wikipedia.org#cite_ref-newin-2.0_7-0
[123]: https://en.wikipedia.org#cite_ref-newin-2.0_7-1
[124]: https://en.wikipedia.org#cite_ref-newin-2.0_7-2
[125]: https://web.archive.org/web/20091214142515/http://www.amk.ca/python/2.0
[126]: http://www.amk.ca/python/2.0/
[127]: https://en.wikipedia.org#cite_ref-3.0-release_8-0
[128]: https://en.wikipedia.org#cite_ref-3.0-release_8-1
[129]: https://www.python.org/download/releases/3.0/
[130]: https://en.wikipedia.org#cite_ref-pep-3000_9-0
[131]: https://en.wikipedia.org#cite_ref-pep-3000_9-1
[132]: https://en.wikipedia.org#cite_ref-pep-3000_9-2
[133]: https://www.python.org/dev/peps/pep-3000/
[134]: https://en.wikipedia.org#cite_ref-svn-history_10-0
[135]: https://raw.githubusercontent.com/python/cpython/master/Misc/HISTORY
[136]: https://en.wikipedia.org#cite_ref-reduce-fate_11-0
[137]: http://www.artima.com/weblogs/viewpost.jsp?thread=98196
[138]: https://en.wikipedia.org#cite_ref-12
[139]: https://web.archive.org/web/20070501080219/http://www.amk.ca/python/writing/12-14
[140]: http://www.amk.ca/python/writing/12-14
[141]: https://en.wikipedia.org#cite_ref-13
[142]: https://www.python.org/doc/essays/cp4e/
[143]: https://en.wikipedia.org#cite_ref-14
[144]: https://web.archive.org/web/20070329060757/http://www.python.org/cp4e/
[145]: https://www.python.org/cp4e/
[146]: https://en.wikipedia.org#cite_ref-lib-history_15-0
[147]: https://en.wikipedia.org#cite_ref-lib-history_15-1
[148]: https://web.archive.org/web/20070329061639/http://www.python.org/doc/2.5/lib/node951.html
[149]: https://www.python.org/doc/2.5/lib/node951.html
[150]: https://en.wikipedia.org#cite_ref-pep-227_16-0
[151]: https://www.python.org/dev/peps/pep-0227/
[152]: https://en.wikipedia.org#cite_ref-17
[153]: https://web.archive.org/web/20080917162106/http://python.org/doc/2.2.3/whatsnew/sect-rellinks.html
[154]: https://www.python.org/doc/2.2.3/whatsnew/sect-rellinks.html
[155]: https://en.wikipedia.org#cite_ref-pep-255_18-0
[156]: https://www.python.org/dev/peps/pep-0255
[157]: https://en.wikipedia.org#cite_ref-19
[158]: https://en.wikipedia.org#cite_ref-20
[159]: https://en.wikipedia.org#cite_ref-pep-361_21-0
[160]: https://www.python.org/dev/peps/pep-0361/
[161]: https://en.wikipedia.org#cite_ref-whatsnew2.7_22-0
[162]: https://docs.python.org/release/2.7/whatsnew/2.7.html
[163]: https://en.wikipedia.org#cite_ref-pep-404_23-0
[164]: https://www.python.org/dev/peps/pep-0404/
[165]: https://en.wikipedia.org#cite_ref-24
[166]: http://www.i-programmer.info/news/216-python/7179-python-27-to-be-maintained-until-2020.html
[167]: https://en.wikipedia.org#cite_ref-25
[168]: http://intertwingly.net/blog/2007/09/01/2to3
[169]: https://en.wikipedia.org#cite_ref-26
[170]: http://python-notes.curiousefficiency.org/en/latest/python3/questions_and_answers.html#other-changes
[171]: https://en.wikipedia.org#cite_ref-27
[172]: https://www.python.org/dev/peps/pep-3105/
[173]: https://en.wikipedia.org#cite_ref-28
[174]: http://www.artima.com/weblogs/viewpost.jsp?thread=211200
[175]: https://en.wikipedia.org#cite_ref-29
[176]: https://www.python.org/dev/peps/pep-3107/
[177]: https://en.wikipedia.org#cite_ref-30
[178]: https://www.python.org/dev/peps/pep-3137/
[179]: https://en.wikipedia.org#cite_ref-31
[180]: https://www.python.org/download/releases
[181]: https://en.wikipedia.org#cite_ref-32
[182]: /w/index.php?title=History_of_Python&action=edit§ion=11 
