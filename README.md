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

| Character | UTF-16 Hex Value | Number of times it apperars |
| ----------- | ----------- | | ----------- |
| Space | HEX | 62782 | 
| e | HEX | 35770 |
| t | HEX | 26376 | 
| a | HEX | 22352 |
| o | HEX | 22329 | 
| i | HEX | 21906 |
| n | HEX | 21665 | 
| s | HEX | 20873 |
| r | HEX | 16673 | 
| h | HEX | 16508 |
| l | HEX | 12460 | 
| d | HEX | 10431 |
| c | HEX | 7879 | 
| u | HEX | 7865 |
| f | HEX | 7104 | 
| m | HEX | 7088 |
| , | HEX | 5623 | 
| p | HEX | 5618 |
| y | HEX | 5417 | 
| g | HEX | 5102 |
| w | HEX | 5088 | 
| b | HEX | 3465 |
| v | HEX | 3162 | 
| - | HEX | 2851 |
| " | HEX | 1722 | 
| . | HEX | 1530 |
| k | HEX | 1422 | 
| E | HEX | 1263 |
| I | HEX | 1167 | 
| T | HEX | 1124 |
| A | HEX | 880 | 
| S | HEX | 791 | 
| O | HEX | 774 | 
| N | HEX | 663 | 
| R | HEX | 634 | 
| ; | HEX | 499 | 
| x | HEX | 472 | 
| L | HEX | 435 | 
| G | HEX | 418 | 
| H | HEX | 414 | 
| C | HEX | 395 | 
| : | HEX | 377 | 
| ! | HEX | 374 | 
| P | HEX | 367 | 
| M | HEX | 332 | 
| q | HEX | 331 | 
| W | HEX | 330 | 
| U | HEX | 318 | 
| D | HEX | 308 | 
| F | HEX | 306 | 
| ? | HEX | 288 | 
| j | HEX | 285 | 
| B | HEX | 212 | 
| ' | HEX | 204 | 
| ( | HEX | 175 | 
| ) | HEX | 175 | 
| z | HEX | 171 | 
| 1 | HEX | 170 | 
| 2 | HEX | 161 | 
| Y | HEX | 146 | 
| V | HEX | 131 | 
| 3 | HEX | 67 | 
| 5 | HEX | 66 | 
| 6 | HEX | 64 | 
| 4 | HEX | 64 | 
| K | HEX | 63 | 
| 7 | HEX | 62 | 
| 8 | HEX | 61 | 
| 9 | HEX | 58 | 
| 0 | HEX | 51 | 
| J | HEX | 44 | 
| Q | HEX | 28 | 
| X | HEX | 21 | 
| Open Square Bracket | HEX | 9 | 
| Closed Square Bracket | HEX | 9 | 
| Z | HEX | 7 | 
| _ | HEX | 4 | 
| ﻿ | feff | 1 |
