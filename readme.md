# Concrete LGC (Latin/Greek/Cyrillic) fonts

This is but a brief description of the Concrete LGC fonts.

# Motivation

There is already a set of Concrete Latin/Greek/Cyrillic fonts in the [CMUnicode bundle on CTAN](https://ctan.org/pkg/cm-unicode). That set, however, adopts the classical, sans-serif Didot cut as the "Roman" one, thus breaking the appearance of the regular, heavy square serifs of Knuth's Concrete. 

This refurbished version of the Concrete LGC fonts aims to fix that irregularity by adopting the squared serifed version of Beccari's Greek fonts for the "Roman" type, and a slightly oblique version of the classical Didot cut for italics. Once the outlines for the Greek script were produced from Knuth and Beccari's sources (kindly thanks to the latter, who fixed a bug in the lowercase Greek in the process) via [mftrace](http://lilypond.org/mftrace/), they were merged with Nikola Lečić and Andrey Panov's CMUnicode Latin and Cyrillic, substituting their Greek choice. The name change is necessary to keep the other fonts working in the same system. 

This distribution provides the [FontForge](https://fontforge.org/en-US/) source and a simple script to generate the fonts, and the fonts themselves as OpenType binaries.

# Bugs

Some kernings need adjusting; I am distributing this Beta version in the hope that some people with more time and expertise may contribute with fixes.

Luis Rivera
@@jarnosz on GitHub

December 24, 2022
