- Markdown is a lightweight markup language with a plain text formatting syntax
- It can be converted into HTML/XHTML and other formats
- Its main purpose is readability and ease of use.

It is used for:
 - Readme files (Github, etc)
 - Forum & blog posts
 - Used in many static site generators

Save in README.md
Use the VSCode extension (Auto-Open Markdown Preview)


NOTE: You can use escape characters using \

   ----- Table of contents ----
1. Writing Headings
2. Writing Paragraphs
3. LIsts
4. URL
5. Inline Code
6. Block of code
7. Images
8. Block quotes
9. Tables
10. Bold, Italic, strikethrough
11. Horizontal lines
12. Task list

1. ======= WRITING HEADINGS ===========
# Begin the title with the '#' symbol, Similar to HTML h1. Note space between # and the text
## Similar to HTML h2.
Similarly, it runs from a single # through to 6#, similar to HTML h1 through h5

2. ====== Writing Paragraphs ============
Simply write the paragraph text like this, without the '#' symbol.

NOTE: To give a line break, give double line space between texts


3. ===== LISTS ======= 
   a. ---- Unordered list ----
 - List 1  // OR   * List 1
 - List 2
   - List 2A   //double space before -
   - List 2B

   b. ---- Ordered list ----

 1. List 1
 1. List 2
 1. List 3
    1. List 3a  //triple space before 1
    1. List 3b


4. ==== URL ==========
[This is the linke to google website](http://www.google.com)

[This is the linke to google website](http://www.google.com, "This is the title when hover over the link)

Click  [Here](http://www.google.com, "Google") to visit google


5. ==== INLINE CODE ====
Include any inline code by surrounding it with a `backtik` symbol, ie `<p>This is a paragraph </p>`

6. ==== BLOCK OF CODE (Supported in github, not default to markdown) ====

Use 3 ```backtiks```

```html
<p> A paragraph example</p>

```

```javascript
let num = Math.random()

```

7. ===== IMAGES ====
 ![alt text](https://picsum.photos/200/200)
 ![alt text](https://markdown-here.com/img/icon256.png)


8. ==== BLOCK QUOTES ===
 > This is a blockquote


9. ==== TABLES (Supported in github, not default to markdown) =====
 | header 1 | Header 2 | Header 3 |
 | --- | --- | --- |
 | Content 1 | Content 2 | Content 3 |
 | Content 4 | Content 5 | Content 6 |


10. ==== BOLD, ITALIC, STRIKETHROUGH ===
    This text is *ITALIC*, also _ITALIC_, while this one is **BOLD**, and this is ~~STRIKETHROUGH~~


11. === HORIZONTAL LINES =======
---
___

Using either of the above adds horizontal lines, similar the HTML's <hr> 


12. ==== TASK LIST =====

* [x] Task 1
* [x] Task 2
* [ ] Task 3