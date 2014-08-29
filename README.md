## Inconsolata, with italics and bold, in .otf format

[Inconsolata](http://en.wikipedia.org/wiki/Inconsolata) is a nice 
monospace programming font. Unfortunately, it doesn't come with italics 
and bold versions by default. I have used a version from 
[MihailJP/Inconsolata-LGC](https://github.com/MihailJP/Inconsolata-LGC) 
that does, and converted them using [FontForge](http://fontforge.org/) 
to .otf (Open Font Format) for easy installation.

### Install

If it doesn't already exist, make a directory `~/.fonts/Library` and put 
these files there. That's it. Now other software should be able to find 
and use the Inconsolata LGC fonts. Works in Ubuntu, at least.

Then for Emacs (if you use Emacs) put

    emacs.font:      InconsolataLGC-12

in your `.Xresources` (or some other font size than 12) and say `xrdb 
-merge ~/.Xresources`.

The previous README from [MihailJP/Inconsolata-LGC](https://github.com/MihailJP/Inconsolata-LGC)
is here:

    Inconsolata LGC
    ---------------
    
    Inconsolata is one of the most suitable font for programmers created by Raph
    Levien. Since the original Inconsolata does not contain Cyrillic alphabet,
    it was slightly inconvenient for not a few programmers from Russia.
    
    Inconsolata LGC is a modified version of Inconsolata with added the Cyrillic
    alphabet which directly descends from Inconsolata Hellenic supporting modern
    Greek.
    
    Inconsolata LGC is licensed under SIL OFL.
    
    
    Inconsolata LGC changes:
    * Cyrillic glyphs added.
    * Italic and Bold font added.
    
    Changes inherited from Inconsolata Hellenic:
    * Greek glyphs.
    
    Changes inherited from Inconsolata-dz:
    * Straight quotation marks.
