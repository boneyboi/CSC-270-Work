# Nietzsche, *Beyond Good and Evil*

**Status**: Completed as of 12/17/2019

## Bibliography
Text: `urn:cts:fuTexts:nietzsche.goodandevil.siglin:`

Fredrich Nietzsche is a German philosipher, composer, and poet born on October 15th, 1844. Nietzshce published many nihilist works over his lifetime, *Beyond Good and Evil* being the 9th entry in 1886 after such works as *The Birth of Tragedy* and *On Truth and Lies in a Nonmoral Sense*.

*Beyond Good and Evil* discusses multiple topics throught the work, including the relationships between opposite ideas, Nietzshe's views on the pursit of truth by the philosophical community, as well as other various topics he discusses through poems.

The file: `text/nieztzche_bge.cex`

## Desription of Repo and how to use it's contents

This repository is a way to display *Beyond Good and Evil* in html as well as a way to validate the characters for it. It can also be used to run any sort of script on the text.

### Requirements
-Java JDK 1.8+
-SBT installed and on PATH

### Running scripts
- Download or clone the repository.
- Go to the root folder for the repository.
- Run `sbt console`.
- Run a script `scala> :load yourfolder/yourscript.sc`.

## Character Validation
This is a table with the characters that have been validated by `scripts/corpus-char-validate.sc`, meaning each character in the text is unique and means something else from everyother character.

| Character | Hex Value | Number of times it apperars |
| ----------- | ----------- | ----------- |
| Space | 20 | 62782 | 
| e | 65 | 35770 |
| t | 74 | 26376 | 
| a | 61 | 22352 |
| o | 6F | 22329 | 
| i | 69 | 21906 |
| n | 6E | 21665 | 
| s | 73 | 20873 |
| r | 72 | 16673 | 
| h | 68 | 16508 |
| l | 6C | 12460 | 
| d | 64 | 10431 |
| c | 63 | 7879 | 
| u | 75 | 7865 |
| f | 66 | 7104 | 
| m | 6D | 7088 |
| , | 2C | 5623 | 
| p | 70 | 5618 |
| y | 79 | 5417 | 
| g | 67 | 5102 |
| w | 78 | 5088 | 
| b | 62 | 3465 |
| v | 76 | 3162 | 
| - | 2D | 2851 |
| " | 22 | 1722 | 
| . | 2E | 1530 |
| k | 6B | 1422 | 
| E | 45 | 1263 |
| I | 49 | 1167 | 
| T | 54 | 1124 |
| A | 41 | 880 | 
| S | 53 | 791 | 
| O | 4F | 774 | 
| N | 4E | 663 | 
| R | 52 | 634 | 
| ; | 3B | 499 | 
| x | 78 | 472 | 
| L | 4C | 435 | 
| G | 47 | 418 | 
| H | 48 | 414 | 
| C | 43 | 395 | 
| : | 3A | 377 | 
| ! | 21 | 374 | 
| P | 50 | 367 | 
| M | 4D | 332 | 
| q | 71 | 331 | 
| W | 57 | 330 | 
| U | 55 | 318 | 
| D | 44 | 308 | 
| F | 46 | 306 | 
| ? | 3F | 288 | 
| j | 6A | 285 | 
| B | 42 | 212 | 
| ' | 27 | 204 | 
| ( | 28 | 175 | 
| ) | 29 | 175 | 
| z | 7A | 171 | 
| 1 | 31 | 170 | 
| 2 | 32 | 161 | 
| Y | 59 | 146 | 
| V | 56 | 131 | 
| 3 | 33 | 67 | 
| 5 | 35 | 66 | 
| 6 | 36 | 64 | 
| 4 | 34 | 64 | 
| K | 4B | 63 | 
| 7 | 37 | 62 | 
| 8 | 38 | 61 | 
| 9 | 39 | 58 | 
| 0 | 30 | 51 | 
| J | 4A | 44 | 
| Q | 51 | 28 | 
| X | 58 | 21 | 
| Open Square Bracket | 5B | 9 | 
| Closed Square Bracket | 5D | 9 | 
| Z | 5A | 7 | 
| _ | 5F | 4 | 
| ﻿ | EF | 1 |
