# Markdown

## ![README 101](https://miro.medium.com/max/700/1*YuZrmECPHDAyz5d3glXg2Q.png)
### What is it?

**_A [README](https://en.wikipedia.org/wiki/README)_** is a text file that introduces and explains a project. It contains information that is commonly required to understand what the project is about.

### Why should I make it?

It's an easy way to answer questions that your audience will likely have regarding how to install and use your project and also how to collaborate with you.

### Who should make it?

Anyone who is working on a programming project, especially if you want others to use it or contribute.

### When should I make it?

Definitely before you show a project to other people or make it public. You might want to get into the habit of making it the first file you create in a new project.

### Where should I put it?

In the top level directory of the project. This is where someone who is new to your project will start out. Code hosting services such as [GitHub](https://github.com/), [Bitbucket](https://bitbucket.org/), and [GitLab](https://about.gitlab.com/) will also look for your README and display it along with the list of files and directories in your project.

### How should I make it?

While **_READMEs_** can be written in any text file format, the most common one that is used nowadays is _[Markdown](https://en.wikipedia.org/wiki/Markdown)_. It allows you to add some lightweight formatting. You can learn more about it at the CommonMark website, which also has a helpful [reference guide](https://commonmark.org/help/) and an interactive tutorial.


# How to create a Readme.md file?

In this blog, you will learn about the Markdown file or also called the .md file.

1. [What is an Md file](#what-is-an-md-file)?
2. [Where an Md file is used](#where-an-md-file-is-used)?
3. [How to Create an Md File](#how-to-create-a-readmemd-file)?
4. [How to write an Md file with proper Syntax](#how-to-write-an-md-file-with-proper-syntax)?
5. [How to Read/Open an Md File](#how-to-readopen-an-md-file)?  

### What is an Md file?

#### History of Md file

Markdown language was created by _John Gruber_ and _Aaron Swartz_ in 2004 with the idea of enabling people to write using easy to read and write plain text format and with the option of converting it to XHTML or HTML. The goal behind its design was readability — language is readable as it is, without looking like it has been tagged or added with formatting instructions as done in markup languages like RTF or HTML where tags and formatting instructions are obvious. The basic inspiration is using existing conventions for marking up plain text in an email.

>A MARKDOWN file is a text file created using one of several dialects of the Markdown language. It uses plain text format but also contains in line text symbols which specify how to format the text (e.g., bold,italics, indentation, headers, etc). It is a lightweight scripting language

A file with .md or .MARKDOWN extension is a Markdown doc. file. It’s nothing but a plain text file that uses the Markdown language to describe how to convert a text document to HTML. It takes all the text from the markdown file and converts it into XHTML or HTML through a markdown app or a compiler.

![compiler](https://miro.medium.com/max/507/1*5gXI0AudBycY_hSz-oAwSg.png)

#### Where an Md file is used?

Markdowns are rapidly used in content writing in many websites, blog posts. Some popular repository providers like GitHub, GitLab, and bitbucket use the readme.md file as a file descriptor. It is used to write an installation guide or basic documentation inside the project directory. It contains information about a particular section where it is generally kept.

![file](https://miro.medium.com/max/700/1*flaQu7uVv90K50DZO3lTVQ.png)

>It is Mostly used inside github, gitlab and in other documentation work.

#### How to Create an Md File?

**INSTRUCTIONS**  

Before creating a Readme.md file you need a text editor. There are plugins for many editors (e.g. Atom, Emacs, Sublime Text, Notepad++, Vim, and Visual Studio Code) or simply notepad.

Steps to create a Readme.md file :

1. Open any text editor or notepad.
2. Create a new file from — →file →new file.
3. Save the file as Readme.md or any suitable name with .md extension.
4. Your file is created.

>Note : We will be using Visual Studio Code (VS Code) for demonstration here.

#### How to write an Md file with proper Syntax?

**TEXT**

Ways to display a Normal, Bold, Italic, Strikethrough text.

* Simple text :- Can be simply typed → Text
* Italic text :- Can be typed between pair of Underscores → _text_
* Bold text :- Can be typed between a pair of two Asterisk → **text**
* Strikethrough :- Can be typed between a pair of two Tilde → ~~text~~

![example](https://miro.medium.com/max/700/1*D_L7ckXlvopBwqg6gvfUMw.png)

**HEADING**

Heading can be typed in different sizes ranging from 1–6 by adding hash/pound. It can be typed in the following ways.  


*Max size 1 → #Heading 1

*Size 2 → ##Heading 2

*Size 3 → ###Heading 3

*Size 4 → ####Heading 4

*Size 5→ #####Heading 5

*Min Size 6 → ######Heading 6

![heading](https://miro.medium.com/max/700/1*9cKdze0h33WxBo3_ZrtEFA.png)

**QUOTE and COPYRIGHT**

To add Quote simply use strict inequality GREATER THAN symbol.

> Your Quote will be typed here

For COPYRIGHT sign follow this method.

&copy;  (& copy)

![quote](https://miro.medium.com/max/700/1*xE5KKq99szw0HMOCrx94_g.png)

**HYPERLINK**

To add a hyperlink in your .md file follow this rule.

* Type the name of hyperlink inside square brackets i.e. [ ]
* And type/paste the link or URL inside round brackets i.e. ( )
Example

>[YouTube] (https://www.youtube.com “Youtube”)
 
![hyperlink](https://miro.medium.com/max/700/1*GMRQEIKY9KAECbFCarhC_Q.png)

**IMAGE FILE**

To add an image file in your .md file follow the following rules.

* Type the image name inside square brackets after adding an Exclamation point/BANG → ! [ ].
* And type/paste the image link or URL inside round brackets i.e. ( )

Example

>! [Earth] (https://www.sciencealert.com/the-earth-is-moving-substantially-less-because-of-the-global-pandemic)

![image](https://miro.medium.com/max/700/1*s1esK-AJevTZWnQ76WY9cA.png)

**CODE**

To add a code in .md file type the code in between a pair of **_BACKQUOTE_** (`code`).

![code](https://miro.medium.com/max/700/1*0a8eejNPvvaUhlPZymu79w.png)

**CODE BLOCKS**

To add a Block of multiple lines of codes in a .md file, type it between a pair of **_3 BLOCKQUOTE_** (```code blocks```).

![code blocks](https://miro.medium.com/max/700/1*0a8eejNPvvaUhlPZymu79w.png)

**TABLE**

To create a table in a .md file follow the instructions using the image(Table for car model) as reference.

![table](https://miro.medium.com/max/700/1*47aIYxGv2uVfba61gJD0Iw.png)

* In the line-3 heading of the table is added separated by a pipe ( | )
* In the line-4 size is provided for the content of table using dash (-), no of dashes represent the size of that particular column, any character/word typed cannot exceed the size provided using dashes.
* In the line-5,6 contents of the table are added.
>NOTE: Content of table (character/word/no.) should not exceed the size provided, if it is exceeding increase the size by adding more dashes.

**LIST**

To create a List(ordered/unordered) follow the codes are given shown below.

![list](https://miro.medium.com/max/700/1*o8B0wczLfqh80Rx2oja0Qw.png)

**TASK LIST**

To make a task list in a .md file, add a dash(-) followed by square brackets [ ] further followed by task.

![task](https://miro.medium.com/max/700/1*gO7PWYdTa9xcANHH36Udaw.png)

**LINES**

There are many ways to create a line inside a .md file some of them are shown below.

To make a simple line use 3 dashes or asterisk.

>(- - -) or (***)

![lies](https://miro.medium.com/max/700/1*S1fYqrRhKSAefkgWxal3og.png)

**ESCAPE CHARACTER**

To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\) in front of the character.

>\* Without the backslash, this would be a bullet in an unordered list.
>The rendered output looks like this:
>* Without the backslash, this would be a bullet in an unordered list.

_Markdown provides backslash escapes for the following characters_:

* \ backslash
* ` backtick
* *asterisk
* _ underscore
* {} curly braces
* [] square brackets
* () parentheses
* #hash/pound mark
* +plus sign
* -dash (hyphen)
* . dot
* ! exclamation mark

#### How to Read/Open an Md File?

To Read/Open a .md file you can use any text editor. There are plugins for many editors (e.g. Atom, Emacs, Sublime Text, Vim, and Visual Studio Code) that allow you to preview Markdown while you are editing it.

You can also use a dedicated Markdown editor like Typora or an online one like StackEdit or Dillinger. You can even use the editable template below.

Instructions for VS code users.
* Create a new file from — →file →new file.
* Type as per your requirement inside the file using the following syntax provided above.
* Save the file as Readme.md or any suitable name with .md extension.
* Then press Ctrl+Shift+V in the editor.
* Now you can view the preview window of your .md file.

![vscode](https://miro.medium.com/max/700/1*AOFSbEBus9LDHr3eZWSc7w.png)



For java script:

```javascript
console.log("Hello")
```
For python:

```python
print(Hello)
```

[^1]: (This is to refer a stable)


[]:
[]:
[]:
[]:
[]: