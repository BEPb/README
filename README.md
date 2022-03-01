![Profile views](https://gpvc.arturio.dev/BEPb) ![GitHub top language](https://img.shields.io/github/languages/top/BEPb/README) ![GitHub language count](https://img.shields.io/github/languages/count/BEPb/README)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/BEPb/README)
![GitHub repo size](https://img.shields.io/github/repo-size/BEPb/README) ![GitHub](https://img.shields.io/github/license/BEPb/README) ![GitHub last commit](https://img.shields.io/github/last-commit/BEPb/README)

![GitHub User's stars](https://img.shields.io/github/stars/BEPb?style=social)
<p align="left">
<img src="https://visitor-badge.laobi.icu/badge?page_id=BEPb.README" alt="visitors"/>
</p>

Read in other languages: [English](README.md), [हिन्दी](README.hindi.md), [中國人](README.chinese.md)

# All about README.md file markup


## Where did the term "README" come from? (Etymology)

Important information that the user should read before continuing, project descriptions on GitHub in the language
markdown markup is placed in the file "README.md"

The term dates back to at least the 1970s, the time when informational paper notes were placed on stacks.
punched cards "READ ME!" scribbled on them describing their use. Possibly titled README
could be a playful nudge to Lewis Carroll's Alice's Adventures in Wonderland, which has a potion and cake with
labeled "DRINK ME" and "EAT ME" respectively.

The README pattern displayed in capital letters is a consistent aspect throughout history.
In addition to the visual expressiveness of using capital letters, UNIX systems sort capital letters before
in lowercase letters, conveniently placing README before the rest of the contents of the directory.



## Table of contents

1. [Horizontal-line](#Horizontal-line)
2. [Title](#Title)
3. [Text](#Text)
   * 3.1. plain text
   * 3.2. One line of text
   * 3.3. Multiline text
   * 3.4. Text selection
   * 3.5. Line wrapping
   * 3.6. Italics
   * 3.7. Fatty
   * 3.8. Strikethrough
4. [Insert tables](#Insert-tables)
5. [Lists](#Lists)
    * 5.1. Marked
    * 5.2. Numbered
6. [Links](#Links)
    * 6.1. Text hyperlink
    * 6.2. Image link
7. [Useful links](#Useful-links)
    * 7.1. Shields
    * 7.2. Emoji
8. [Hidden menu](#Hidden_menu)

    
## Horizontal line

A horizontal line (separating line) can be obtained in three ways:
* *** (using three consecutive '*' (asterisk))、
***
* --- (using three consecutive '-' (dash))、
---
* ___ (using three consecutive '_' characters (underscore))
___

they all display the horizontal line effect
____

[Back to Table of Contents](#Table-of-Contents)
____
## Title

The heading (font) size can be 6 levels, it depends on the number of `#` (pound) characters at the beginning of the line.


```
# First level heading
## Heading of the second level
### Third level heading
#### Fourth level heading
##### Level 5 heading
###### Level 6 heading
```

# First level heading
## Heading of the second level
### Third level heading
#### Fourth level heading
##### Level 5 heading
###### Level 6 heading

Heading 1 (another way)
=
A first level heading can also be created with one or more '=' characters placed on
line following the title:

```
Heading 1
=
```

Heading 2 (another way)
-
A second level heading can also be created with one or more '-' characters placed on
line following the title:

```
Heading 2
-
```

[Back to Table of Contents](#Table-of-Contents)
____

## Text
### 3.1. plain text
Here the usual text is displayed, without any manipulations.


[Back to Table of Contents](#Table-of-Contents)
____
### 3.2. One line of text
    text on one line

Add 4 spaces at the beginning of the line and your text will be highlighted in a separate window, as in the example. Sometimes it works on
tab, but not always.... the tab character is sometimes indented by 3 or more spaces.


[Back to Table of Contents](#Table-of-Contents)
____
### 3.3. Multiline text
    HERE LIES A BIG STUDENT;
    HIS FATE IS NEGOTIABLE.
    CARRY AWAY MEDICINE:
    THE ILLNESS OF LOVE IS INCURED!

Add 4 spaces at the beginning of each line and your text will be highlighted in a separate window, as in the example.

[Back to Table of Contents](#Table-of-Contents)
____
### 3.4. Text selection
The above examples will not be able to keep the indentation of complex text on each line, for this purpose use in
three backticks "```", and they must be on separate lines before and after the text, respectively.

```
"Strive not for success, but for the values that it gives."
                                          Albert Einstein
```
If you only use a pair of backticks, then your text will be highlighted, but not indented. Same way
you can highlight individual words in the text.

``
Life is what happens to you while you are making plans.
                                                      John Lennon
``

``Logic`` can take you from point A to point B, and ``imagination`` can take you anywhere. (Albert Einstein)

But that's not all, often we feel the need to place code fragments, it is desirable not only to keep indents,
but also highlight with color, for this you need to specify the programming language after the first three quotes
```python
from django.contrib import admin
# admin settings
# Register your models here.

from .models import Phonenumber, Division, MilitaryUnit


class PhonenumberAdmin(admin.ModelAdmin): # describe the Directory section of the admin panel
    # specify the displayed fields
    list_display = (
        'id',
        'military_unit', # specify the military unit from the MilitaryUnit table
        'division', # specify the division from the Division table
        'subdivision',
    )
```
____

[Back to Table of Contents](#Table-of-Contents)
____
### 3.5. Line wrapping
Perhaps this is not usual and not familiar, but when you press the "Enter" button, your text will still be displayed in one
line, and in order for your transfer to work, you need to add two spaces at the end of the line

Or just add an empty string, i.e. press "Enter" 2 times. In this case, the transfer effect will be achieved, but
line spacing will be larger.

[Back to Table of Contents](#Table-of-Contents)
____
### 3.6. Italics
Place text between two characters '*' (asterisks) or '_' (underscores) and it will turn into
*italic text* or _italic text_
```
*italic text* or _italic text_
```
[Back to Table of Contents](#Table-of-Contents)
____
### 3.7. Fatty
Place text between two double '*' (asterisks) or '_' (underscore) characters and it will turn into
__bold text__ or **bold text**
```
__bold text__ or **bold text**
```
Text between three characters '*' (asterisks) or '_' (underscores) turns it into bold italic text:
___Bold Italic___ or ***Bold Italic***
```
___Bold Italic___ or ***Bold Italic***
```

[Back to Table of Contents](#Table-of-Contents)
____
### 3.8. Strikethrough
Place text between two double '~' characters and it will turn into
~~Strikethrough TEXT~~
```
~~Strikethrough TEXT~~
```

[Back to Table of Contents](#Table-of-Contents)
____
## Insert tables

simple table
```
|Author|Andrey Marinchenko|
|---|---|
|Profession| python-developer|
|Article| About markup in the README|
```
|Author|Andrey Marinchenko|
|---|---|
|Profession| python-developer|
|Article| About markup in the README|

[Back to Table of Contents](#Table-of-Contents)
____

## Lists
### 5.1. Marked
A bulleted list is formed by the characters -, + or * that begin each new line of the list
- first
- second
- the third
### 5.2. Numbered
The numbered list is created like regular line numbering,
1. first
1.1. first subparagraph
1.2. second subparagraph
1.3. third subparagraph
2. second
3. third
4. fourth

[Back to Table of Contents](#Table-of-Contents)
____
## Links
## 6.1. Text hyperlink
## Link to external URL
We can just add a link from the browser https://github.com/BEPb and it will work, but if we want to hide it
after the text, the link must be placed in parentheses, and the text in square brackets immediately before the link
```
Click here ---> [tyts](https://github.com/BEPb)
```
Click here ---> [tyts](https://github.com/BEPb)
    
## Link to text inside README.md
If we form a link inside the README.md file, then we should remember that we can only refer to headers,
[See "Heading" section](#Heading)
```
[See "Heading" section](#Heading)
```
But what if the title consists of several words?... You need to replace all spaces with '-' as a section about
[Horizontal line](#Horizontal-line)
```
[Horizontal line](#Horizontal-line)
```
## 6.2. Image link
Everything works exactly the same combination of exclamation point + square brackets + parentheses
```
![Doesn't matter](https://avatars.githubusercontent.com/u/57312267?v=4 "caption image on hover")
```
![Doesn't matter](https://avatars.githubusercontent.com/u/57312267?v=4 "caption image on hover")

If you have previously created a folder with images that you wish to use in your README file, then for
displaying such images, you must specify the relative address of your file in the repository, for example, in my
the media folder contains an image called super.jfif, to display you need to enter
```
![](./media/super.jfif)
```
![](./media/super.jfif)

[Back to Table of Contents](#Table-of-Contents)
____
### Useful links

https://shields.io/ - If you want to add shields, for example those at the beginning of this file, then
go to the site, select a shield, usually type in the name on the gihab, the name of the repository and copy the code of the shield into
your readme file.

https://github.com/BEPb/README/blob/master/emogi.md - If you want to decorate your readmi file with emoji
:smiling_imp: , :innocent: then just copy the code from the table opposite the one you need.

### Hidden menu
</b></details>

<details>
<summary>What do I need to do to get collapsible text?</summary><br><b>

Copy the given code and paste your blocks and symbols
```
</b></details>
<details>
<summary> The name of your hidden text </summary><br><b>

Here is your hidden text
</b></details>

```
 

</b></details>