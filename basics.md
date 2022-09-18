# Sphinx Guide

To get started, clone the GhostBSD documentation repo [here](https://github.com/ghostbsd/documentation). The README has instructions on how to install the tools needed to contribute. There are three ways to set up the dev environment.

1. Follow the README
2. Ignore pip and install everything with pkg
3. Ignore pkg and use [pipenv](https://www.freshports.org/devel/py-pipenv/) for everything. (This is what I was doing but it's slightly more complicated.)

If you follow the steps in the README you should have a live preview running in your browser. I noticed it doesn't always update quite right but it basically works.

You can then write in Markdown syntax and use some HTML for more complicated things. The basic things you'll use are:

Main Heading
============
    Main Heading
    ============
    
### Subheadings
    2 to 4 #'s for example ###Subheadings
    
- Bullet Points

        * Bullet Points

*Italic*, **Bold**, and maybe ***Bold Italic***
    
    *Italic*, **Bold** and maybe ***BOLD Italic***
    
## Images
    ![Alternate text describing the image][path/to/image]
    ![Boot loader selection in GhostBSD installer.](images/full-disk-installation/7-loader-uefi.png)

## External Links
    [text you want to display](URL that you want to link to)
    
## [Internal Links](#Main-Heading)
    [text you want to display](#title-of-section)
    ## [Internal Links](#Main-Heading)
    
## Footnotes[^1]
    Footnotes[^1]
    [^1]: This is a footnote

[^1]: This is a footnote
