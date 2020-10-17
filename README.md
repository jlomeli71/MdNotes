# Markdown mini Tutorial

Markdown is very useful in GitHub readme files, Jupyter Notebooks, and other applications in the web.
It is a simple way to provide format to documentes, and simpler than formating a traditional web page with html, css.
You can use any text editor to write markdown, but there are useful tools to see inmediately the ressults of your markdown, for example if you use Chrome as web browser, you can add the app [Minimalist Markdown](https://chrome.google.com/webstore/detail/minimalist-markdown-edito/pghodfjepegmciihfhdipmimghiakcjf?hl).

I do not intend to present all Markdown options (although I plan to improve it), only some usefull ones, but I encourage anyone reading to explore other tutorials, see markdown files form diverse sources and explore the code, and use it in your own mardown files, it is really fun.

I have divided this tutorial in several sections. Each part shows an example of how is seen in the browser, and the in the code.  

*****

## Contents
- [Header options](https://github.com/jlomeli71/miniMdTutorial#header-options)
- [Formating text options](https://github.com/jlomeli71/miniMdTutorial#text-options)
- [Quoting text](https://github.com/jlomeli71/miniMdTutorial#quoting-text)
- [List options](https://github.com/jlomeli71/miniMdTutorial#lists-options)
- [Formating a table](https://github.com/jlomeli71/miniMdTutorial#table-format)
- [Adding links](https://github.com/jlomeli71/miniMdTutorial#adding-links)
- [Adding images](https://github.com/jlomeli71/miniMdTutorial#adding-images)
- [Adding videos](https://github.com/jlomeli71/miniMdTutorial#adding-videos)
- [Including code](https://github.com/jlomeli71/miniMdTutorial#including-code)

*****

## Header options
Headers are ussually the first thing you type at the begining of your document. There are several size options dependind on the number of # you type before the text (from 1 to 6). In this example I only show the firt three options.

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
Formating text is very importnat, to highlight or differentiate from the rest of the text. two common options are to use the single characters _ or * for _italic text_ or to use the sma echaracters but double for __bold text__.

_italic text_
> Code:
```
_italic text 1_
```

__bold text__ 
> Code:
```
__bold text 1__
```

*****

## Quoting text
Quoting text is also very common when you want to highligh text from a different author, or copying something from a different source.

> Quoted text

> Code:
```
> Quoted text
```

*****

## Lists options 
Listing data is also a comon way to organize objects or elements in a document. You can use -, +, or * characteres

Example using -:
- list element 1
- list element 2
> Code:
```
- list element 1
- list element 2
```

And if you want to use number your elements in a list is very simple.

Numbered lists:
1. list element numbered 1
2. list element numbered 2
> Code:
```
1. list element numbered 1
2. list element numbered 2

```

Combing lists (sublists)
- list example 1
    + hello
    + world
- list element 2
> Code:
```
- list example 1
    + hello
    + world
- list element 2
```

- list example a
    1. hello
    2. world
- list element b
> Code:
```
- list example a
    1. hello
    2. world
- list element b
```

- [ ] Task 1
- [ ] Task 2 
> Code:
```
- [ ] Task 1
- [ ] Task 2 
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
