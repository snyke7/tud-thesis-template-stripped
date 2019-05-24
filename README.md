# TU Delft Thesis Template, stripped

This repository contains a stripped version of the TU Delft Thesis template, available [here](https://www.tudelft.nl/en/tu-delft-corporate-design/downloads/). That template contains various unused files, cluttering your thesis folder. This repository aims to provide only the files that are actually used. 

Furthermore, it offers a way to install the style locally on Linux-based environments, so that you can use this style without needing to copy all the template files in your thesis folder

## Improvements upon the template
 - Restored title, subtitle, author and affiliate command to original usage with one argument: the content. Changing the color of these texts on the cover can be done with separate `cover{text}color` commands, such as `covertitlecolor`.
 - Added a `nativemath` option to the documentclass, which does not load the `unicode-math` and thus keeps the original math font.
## Local installation on Linux
A bash script called `install_to_texmf` moves the style files to locations in your TEXMFHOME. The TEXMFHOME is a way to make shared styles available to various projects. The correct location for various types of files is described in the [Tex Directory Structure](http://www.tug.org/tds/tds.html#Introduction).
## Testing the template
A bash script called `test_local` can be used to test whether you can compile this template, before installing. Test results are saved in a `test.log` file.
