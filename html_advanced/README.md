HTML, advanced
==============



![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/1f4cd63ecc3a8c03b0f4309b74aca179e225aabf.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241202%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241202T090237Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=52f439b26af9b655d895d80ab5154206f42b5724d39b1fb9cf4d6dbd6bf2a2c9)

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2024/4/04a83a0e813e4ae602915c0d844e5c2ba05602f4.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241202%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241202T090237Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=7addc1a733d0c1a855b36254c7efa5d447eea16d24b9d643e07780b93293b2a8)

Resources
---------

**Read or watch**:

*   [Learn to Code HTML & CSS](/rltoken/D6o845Dj6bWanYggYGQK4A "Learn to Code HTML & CSS") (_until “Creating Lists” included_)
*   [Introduction to HTML](/rltoken/odwyiWUlo7nyK3UR6FUEdg "Introduction to HTML")
*   [MDN](/rltoken/STnL1M-mwzCvnzHtG21XGQ "MDN")

Learning Objectives
-------------------

At the end of this project, you are expected to be able to [explain to anyone](/rltoken/tk1bYe9n6YmcEsF-gwOgMA "explain to anyone"), **without the help of Google**:

### General

*   What is HTML
*   How to create an HTML page from a wireframe
*   What is a markup language
*   What is the DOM
*   What is an element / tag
*   What is an attribute
*   What the purpose of each HTML tag

Requirements
------------

### General

*   All your files should end with a new line
*   A `README.md` file, at the root of the folder of the project is mandatory
*   You are **not allowed** to install, import or use external libraries. This website must be build with only HTML/CSS/JavaScript. No NodeJS, React, VueJS, Bootstrap, etc.
*   Your code should be W3C compliant and validate with [W3C-Validator](/rltoken/czWaAX6ZYwSLoR3bh2Qiqg "W3C-Validator")

_For this project, we expect you to look at these concepts:_

*   [Some pointers about HTML](/concepts/834)
*   [HTML - elements of a web page](/concepts/835)
*   [HTML Foundations](/concepts/836)
*   [HTML - Semantic sectioning elements](/concepts/837)
*   [HTML Semantic Elements](/concepts/838)
*   [HTML Validation](/concepts/839)

Tasks
-----

### 0\. README and objectives!

mandatory

In this and coming projects, you will implement from scratch a webpage from a designer file.

For this first project, you will focus on the HTML structure only - **no CSS, no style - just pure HTML semantic.**

This designer file will be available on [Figma](/rltoken/ChJbK90Un6oS2A6ozdyTQA "Figma") - feel free to create an account to access the final result here:

*   [Page in Figma](/rltoken/lhaBvvfXnyGKs9bRxokWtQ "Page in Figma")
*   [fig file](/rltoken/BOC4LSHhGgn-RudlXjuUKg "fig file")

And “Duplicate to your Drafts” to have access to all design details.

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241202%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241202T090237Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d15a5687ae027b25bc8a94b7bbb6763490a799bcc9de6b4f69111452c9c02ac1)

Important notes with Figma:

*   if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](/rltoken/76O2REi_XN8esxhm9fZg9w "source-sans-pro") and [Spin-Cycle-OT](/rltoken/tIZuYvssJ291nB0BWUl-Tw "Spin-Cycle-OT")
*   some values are in float - feel free to round them

For this task, please write an amazing `README.md`

**Repo:**

*   GitHub repository: `holbertonschool-web-development`
*   Directory: `html_advanced`
*   File: `README.md`


### 1\. Header

mandatory

Let’s start at the top: **the header**

Here is the wireframe of it:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2024/4/f08f357fc2c894d821a29b7f907f26089ec68d86.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241202%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241202T090237Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9ad61348eda07446025f7490242e3cf9ca321b59371e68a3c214c79b302afdc7)

*   Create the HTML skeleton (`html`, `head`, `body`, etc.)

*   In the body, add a `header` tag
*   Inside this `header`:
    *   Add a link element with an image inside
    *   Add a block of 3 link elements

**Repo:**

*   GitHub repository: `holbertonschool-web-development`
*   Directory: `html_advanced`
*   File: `index.html`



### 2\. Banner

mandatory

Now, the banner inside the `main`:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2024/4/d3f0dba16af368a681919fb44306fadfb2499b54.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241202%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241202T090237Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=00b239b3285d0db5e7832ab7272abcecd93f4150406d8686bdf6a6c653e15cba)

Add a `main` tag that has a `section` element inside.

In this `section` element, add:

*   A block containing:
    *   A heading tag (level 1, don’t forget to use the correct heading value)
    *   A text element
    *   A button tag
*   Another block containing:
    *   Another heading tag (level 2, be careful about which one you are using)
    *   A block containing 4 blocks - each block containing:
        *   An image
        *   A heading tag (level 3)
        *   A text

**Repo:**

*   GitHub repository: `holbertonschool-web-development`
*   Directory: `html_advanced`
*   File: `index.html`



### 3\. Quote

mandatory

Under the banner, we will add the quote block:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2024/4/e898eac85272d52f5528ea81678000045a37017a.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241202%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241202T090237Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=81250fd7a0a329a2211f6706af8305b121cc393ea8a59efa24416148f56caa0c)

The quote section is inside the `main`:

*   Create a new `section` for the quote
*   Inside, add a block containing:
    *   An image
    *   Another block with inside:
        *   A blockquote tag
        *   A text tag for the quote author
        *   Another text

**Repo:**

*   GitHub repository: `holbertonschool-web-development`
*   Directory: `html_advanced`
*   File: `index.html`



### 4\. Videos

mandatory

Let’s now add the videos list:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/a5712ac70330c6812c6aee2bf21efe7ac53d1397.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241202%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241202T090237Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=691df882744380a4847bdf8b115d3552212d016cce57e1cc5cd81183d12f18d0)

New `section` containing:

*   A heading tag (level 1)
*   A block containing the 4 video blocks - each of them are composed with:
    *   An image
    *   A heading (level 2)
    *   A text
    *   Add a block for the author information:
        *   An image
        *   A heading (level 3)
    *   A block for the rating:
        *   A block of images (one star = one image)
        *   A text

**Repo:**

*   GitHub repository: `holbertonschool-web-development`
*   Directory: `html_advanced`
*   File: `index.html`



### 5\. Membership

mandatory

The Membership section is similar to the videos list:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/1ddf18bc6d89725de2fde4881e8990fae6d89628.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241202%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241202T090237Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=be3bf865de1fc01eebfd8b3e067023543ee68298bb4a53e104432766eebcffb1)

After the videos list section, add a new `section` containing:

*   A heading (level 1)
*   A block containing 4 block items - each block containing:
    *   An image
    *   A heading (level 2)
    *   A text
*   A button

**Repo:**

*   GitHub repository: `holbertonschool-web-development`
*   Directory: `html_advanced`
*   File: `index.html`



### 6\. FAQ

mandatory

The FAQ section is ending the page before the footer:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/e4b2806abe9edc126fa0d4155aaf5d7e7da479e4.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241202%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241202T090237Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=3bfebb33c62b28f2758e1ac9f7b3f46ca55fa135d013371a35d387eb58302444)

Add a `section` for the FAQ containing:

*   A heading (level 1)
*   A block that contains 2 “row blocks”
*   Each “row block” contains 2 “item blocks”
*   Each “item block” is composed of:
    *   A heading (level 2)
    *   A text

Hint: There is no “row block” tag, “row” is referring to the styling that will be applied in a future project. It just means two “rows” containing two “items” each, also containing their own elements.

**Repo:**

*   GitHub repository: `holbertonschool-web-development`
*   Directory: `html_advanced`
*   File: `index.html`



### 7\. Footer

mandatory

And… the footer!

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/7224527ac842981b3b387cd9d713b4a1b912a487.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241202%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241202T090237Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=80edc596d513becc74387312c34b66ee95bb88a5fb225c27302caf0f2c391949)

After the last `section`, outside of the `main`, add a `footer`:

*   A block (used later for centering the footer content), inside this block:
    *   Another block with:
        *   An image
        *   Another block containing:
            *   3 Images with link
    *   A text

And… that’s it for the moment - the result should not be shiny, don’t worry, CSS is coming…

**Repo:**

*   GitHub repository: `holbertonschool-web-development`
*   Directory: `html_advanced`
*   File: `index.html`


### Tasks list

*   [Mandatory](#mandatory)
*   [Advanced](#advanced)

0\. `README and objectives!`

1\. `Header`

2\. `Banner`

3\. `Quote`

4\. `Videos`

5\. `Membership`

6\. `FAQ`

7\. `Footer`
