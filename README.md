# Markdown mini Tutorial

Markdown is very useful in GitHub readme files, Jupyter Notebooks, and other applications in the web.
It is a simple way to provide format to documentes, and simpler than formating a traditional web page with html, css.
You can use any text editor to write markdown, but there are useful tools to see inmediately the ressults of your markdown, for example if you use Chrome as web browser, you can add the app [Minimalist Markdown] (https://chrome.google.com/webstore/detail/minimalist-markdown-edito/pghodfjepegmciihfhdipmimghiakcjf?hl).

I do not intend to present all the options (although I plan to improve it), only some usefull ones, but I encourage anyone reading to explore other tutorials, se marckdown files form diverse resources and explore the code, and use it in your own mardown files.

I have divided this tutorial in several sections. Each part shows an example of how is seen in the browser, and the n the code. Let´s start with header options, that ussually is the first thing you write in an page using markdown. 

*****

## Contents
- [Header options](link)
- [Formating text options](link)
- [Quoting text](link)
- [List options](link)
- [Formating a table](link)
- [Adding links](link)
- [Adding images](link)
- [Adding videos](link)
- [Including code](link)

*****

## Header options

# Header option 1
```
# Header option 1
```

## Header option 2
```
## Header option 2
```

### Header option 3
```
### Header option 3
```

*****

## Formating text options

_italic text 1_
```
_italic text 1_
```

*italic text 2*
```
*italic text 2*
```

__bold text 1__ 
```
__bold text 1__
```

**bold text 2**
```
**bold text 2**
```

*****

## Quoting text

> Quoted text
```
> Quoted text
```

*****

## Lists options 

Example using -:
- list element 1
- list element 2
```
- list element 1
- list element 2
```

Example using +:
+ list element x
+ list element y
```
+ list element x
+ list element y
```

Example using *:
* list element a
* list element b
```
* list element a
* list element b
```

Numbered lists:
1. list element numbered 1
2. list element numbered 2
```
1. list element numbered 1
2. list element numbered 2

```

Combing lists (sublists)
- list example 1
    + hello
    + world
- list element 2
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
```
- list example a
    1. hello
    2. world
- list element b
```

- [ ] Task 1
- [ ] Task 2 
```
- [ ] Task 1
- [ ] Task 2 
```

*****

## Formating a table

Android | iOS | Windows
--- | --- | ---
Popular apps | Popular apps | Popular apps
Facebook | Instagram | Flirk
Hotmail | Yahoo | Gmail
```
Android | iOS | Windows
--- | --- | ---
Popular apps | Popular apps | Popular apps
Facebook | Instagram | Flirk
Hotmail | Yahoo | Gmail
```

*****

## Adding links

[Desciption](url)
Example:
[Google](http://www.google.com)
```
[Desciption](url)
Example:
[Google](http://www.google.com)
```

*****

## Adding images

![Desciption](url)
Example:
![Cisco Systems](https://www.cisco.com/web/fw/i/logo-open-graph.gif "Cisco Systems")
```
![Desciption](url)
![Cisco Systems](https://www.cisco.com/web/fw/i/logo-open-graph.gif "Cisco Systems")
```

*****

## Adding videos

[![Some text](image link)](video link)
```
[![Some text](image link)](video link)
```

## Including code

For one line code we use a single `:
`single line of code`

For block of code we use this format:
```
import math
def func():
   for if
```

We can specify the code type to include some code formating:
``` python
import math
def func():
   for if
```
