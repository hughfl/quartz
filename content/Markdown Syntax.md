title: "Markdown Syntax"
---
Headers (#)
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

Italic
+ _italics_ (underscore)
+ *italic* (asterisk)

Bold
+ __bold__ (underscore + underscore)
+ **bold** (asterisk + asterisk)

Strikethrough
+ Strikethrough ("~" + "~" text "~" + "~" )
	~~strikethrough~~

Highlight
+ ==highlight==

Lists "- , +, or no."
- number 1 (-)
- number 2

+ number 1 (+)
+ number 2

1. number 1 (Number)
2. number 2


Checklist
+ Cntrl + Enter
+ - [x] 

Links  ([ + ])
+ Link ([ + ] | alias)
+ [[Create Link | Link]]

Link Header (Double Bracket | Header)
+ [[Lab Rack#Software]]

Link Header Alias (Double Bracket | Alias)
+ [[Lab Rack#Software | Lab Software]]

Blocks in Same page (Double Bracket ^ | Alias)
+ [[Lab Rack#^54119c | DB Version]]

External Links
+ www.obsidian.md (url on page)
or
Single Bracket - Link in parenthesis
+ [obsidian](https://obsidian.md) 

Embedding Links
+ "!" before link "![[]]"

Footnote Bracket - caret number 
+ This is a footnote. [^1]

+ [^1]:Definition of the footnote
+ or
+ caret brackets - Link
+ This is a footnote^[Definition of a footnote]
Text caret "|" list
+ Check these lists^[[[Lab Rack#Software | Software List]]]


Tables (Header pipe Header 2)
Header | Text
------------ | --------
cell value | cell value 2





Quotes
> A random quote
>> Author of random quote

Code Snippet
"----" language extension
+ code snippet
"----"

````py
print("Hellow World")
````

````js
print("Hello World")
````























