# Secrets_patterns
Some patterns that can be used on files with ripgrep to (hopefully) find some juicy intel. Some have to be improved to lower the FP rate.


I compiled some old regexes for sensitive files, removed some that are highly likely false positives and modified some so that they should still match relevant stuff but also show less false positives. This is meant as a quick shot solution that allows you to simply use this regexes with ripgrep on any folders/files you downloaded. It's not as full blown as a python or whatever script with proper logic, but can be used for an easy fast quick first look.

Usage:

rg -SUf ~/projects/patterns/patterns your_target_folder

this is compiled from different sources and has grown over a lot of years. Some adjustments have been made to work with ripgrep... However, it is far from perfect, so use with care and feel free to enhance.
