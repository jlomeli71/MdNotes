# Markdown mini Tutorial

Markdown is very useful in GitHub readme files, Jupyter Notebooks, and other applications in the web.
It is a simple way to provide format to documentes, and simpler than formating a traditional web page with html, css.
You can use any text editor to write markdown, but there are useful tools to see inmediately the ressults of your markdown, for example if you use Chrome as web browser, you can add the app [Minimalist Markdown](https://chrome.google.com/webstore/detail/minimalist-markdown-edito/pghodfjepegmciihfhdipmimghiakcjf?hl).

I do not intend to present all Markdown options (although I plan to improve it), only some usefull ones, but I encourage anyone reading to explore other tutorials, see markdown files form diverse sources and explore the code, and use it in your own mardown files, it is really fun.

I have divided this tutorial in several sections. Each part shows an example of how is seen in the browser, and the in the code.  

*****

## Contents
- [Header options](#header-options)
- [Formating text options](#text-options)
- [Quoting text](#quoting-text)
- [List options](#lists-options)
- [Formating a table](#table-format)
- [Adding links](#adding-links)
- [Adding images](#adding-images)
- [Adding videos](#adding-videos)
- [Including code](#including-code)

*****

## Header options
Headers are ussually the first thing you type at the begining of your document. There are several size options dependind on the number of # you type before the text (from 1 to 6). In this example I only show the first three options.

# Header size 1
> Code:
```
# Header size 1
```

## Header size 2
> Code:
```
## Header size 2
```

### Header size 3
> Code:
```
### Header size 3
```

*****

## Text options
Formating text is very important, to highlight or differentiate from the rest of the text. Two common options are to use the single characters _ or * for _italic text_ or to use the same characters but double for __bold text__.

_Italic text_
> Code:
```
_Italic text_
```

__Bold text__ 
> Code:
```
__Bold text__
```

*****

## Quoting text
Quoting text is also very common when you want to highligh text from a different author, or copying something from a different source.

> “Don’t let the noise of others’ opinions 
> drown out your own inner voice.”
>                           ― Steve Jobs

> Code:
```
> Quoted text
```

*****

## Lists options 
Listing data is also a comon way to organize objects or elements in a document. You can use -, +, or * characteres

Example using -:
- list element
- list element
> Code:
```
- list element
- list element
```

And if you want to use number your elements in a list is very simple.

Numbered lists:
1. numbered element
2. numbered element
> Code:
```
1. numbered element
2. numbered element
```

Combing lists (sublists)
- list element
    + hello
    + world
- list element
> Code:
```
- list element
    + hello
    + world
- list element
```

- list element
    1. hello
    2. world
- list element
> Code:
```
- list element
    1. hello
    2. world
- list element
```

- [ ] list element
- [ ] list element
> Code:
```
- [ ] list element
- [ ] list element
```

*****

## Table format
Creating a table is very easy in markdown, and very useful to organize information when lists are not enough.

Android | iOS | Windows
--- | --- | ---
Popular apps | Popular apps | Popular apps
Facebook | Instagram | Flirk
Hotmail | Yahoo | Gmail
> Code:
```
Android | iOS | Windows
--- | --- | ---
Popular apps | Popular apps | Popular apps
Facebook | Instagram | Flirk
Hotmail | Yahoo | Gmail
```

*****

## Adding links
Adding links is very important and not only to add external resources, also to roganize the content of your document.

[Google](http://www.google.com)
> Code:
```
[Google](http://www.google.com)
```

*****

## Adding images
Adding images if you want to provide graphics, for example I use a logo of a well known networking company on this example.

Example:
![Cisco Systems](https://www.cisco.com/web/fw/i/logo-open-graph.gif "Cisco Systems")
> Code:
```
![Cisco Systems](https://www.cisco.com/web/fw/i/logo-open-graph.gif "Cisco Systems")
```

*****

## Adding videos
I do not have a video of my own yet, but you can add any video available on the internet with this format.
[![Some text](image link)](video link)
> Code:
```
[![Some text](image link)](video link)
```

## Including code
Adding code is very common if you are related to software programming or devops.

For one line code we use a single quote at the beggining and end of the code:
`single line of code`

For block of code we triple quotes at the beggining and end of the code:
```
import math
def func():
   for if
```

We can specify the code type to include some code formating, for example in this case we specify python after the first three quotes:
``` python
import math
def func():
   for if
```
