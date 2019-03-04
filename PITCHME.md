@snap[west span-50]
### @color[red](We were pondering about a powerful publishing item.)
@snapend

@snap[east span-50 fragment]
### @color[gray](When we listed our needs, the solution revealed itself!)  
@snapend
---
@transition[zoom]


![](assets/img/cover.png)


<br>

@css[tip](Take on a brief tour of these three options brought by the Jupyter Book.)

@fa[arrow-down fa-3x icon-color]


+++?image=img/bg/green.jpg&position=right&size=65% 100% 
@title[Enliven your papers]

@snap[west span-30]
### @color[gray](Enliven your papers)  
![](assets/img/leafgreen.png)
@snapend


@snap[north-east text-left text-06 span-65]
@snap[text-left text-bold]
@color[white](We know that pages long static PDFs are only a part of your research story.)
@snapend
<br>
@snap[text-left text-bold]
@color[black](Jupyter Books offer you an easy way to supercharge your published work and advance that story!)
@snapend
<br>

@ol[split-screen-list text-09]
- Breathe interactivity into the display items of your old papers. Readers can replicate your key figures and explore your findings like never before. 
- Transform a pseudo-algorithm into an online executable codeblock of your favorite language.   
- Create a digital narrative of your summary analysis, boost up the reproducibility of your study.
@olend

@snapend


+++?image=img/bg/blue.jpg&position=right&size=65% 100% 
@title[Create interactive tutorials]

@snap[west span-30]
### @color[gray](Create interactive tutorials)  
![](assets/img/hatblue.png)
@snapend

@snap[north-east text-left text-06 span-65]

@snap[text-left text-bold]
@color[white](Imagine people who'd like to learn how to use a programming tool or a computational science subject.)  
@snapend
<br>
@snap[text-left text-italic]
@color[white](Bouncing between documents and a software won't make it any easier for them, let alone getting all the neccesary tools working properly.)
@snapend
<br>
@snap[text-left text-bold]
@color[black](Creating interactive tutorials with Jupyter Books, you can take this burden away!)
@snapend
<br>

@ol[split-screen-list text-09]
- Help learners focus their attention on a single page, where implementation meets information. 
- Make all the computational material readily available for executing code online, with one click.  
- Use interactive widgets to create a seamless learning experience. Few gestures can surrogate multiple lines of code.
@olend


@snapend


+++?image=img/bg/orange.jpg&position=right&size=65% 100% 
@title[Share a brief analysis]

@snap[west span-30]
### @color[gray](Share a brief analysis)  
![](assets/img/shareorange.png)
@snapend


@snap[north-east text-left text-06 span-65]

@snap[text-left text-bold]
@color[white](You are onto something interesting, but not ready for writing a paper yet?)
@snapend
<br>
@snap[text-left text-italic]
@color[white](Instead, you may want to share your preliminary results with your community and start a discussion. What if there was a publishing item - of your own - that eases the communication?)
@snapend

Good news, Jupyter Books have you covered!   

@ol[split-screen-list text-09]
- Make the most out of the interactive medium to get your points across clearly.  
- Organize text and one or more computational environment in one place.  
- Feed your data into the publication from your favorite data repository. 
@olend


@snapend



---

@snap[west span-50]
## @color[gray](Let us show you an example!)
@snapend

@snap[east span-50]
![](assets/img/jbook.png)
@snapend

@snap[south]
@fa[arrow-down fa-3x icon-color]
@snapend

+++
@title[Anatomy of a Jupyter Book.]

#### @color[gray](Anatomy of a Jupyter Book)
![](assets/img/gif1.gif)

+++
@title[iframe]

#### @color[gray](Give interactive figure a try!)
@css[tip2](Loading may take a few seconds. Use arrows on the lower right corner for navigation.)


<iframe src="https://brainhack101.github.io/introML-book/01/MAIN_tutorial_intro_to_nilearn.html#interactive-connectome-plotting" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0"></iframe>

+++
@title[oneclick]

#### @color[gray](With one click, you have interactive codeblocks!)
![](assets/img/gif2.gif)

+++
@title[iframe2]

#### @color[gray](Try executable codeblocks!)
@css[tip2](Loading may take a few seconds. Use arrows on the lower right corner for navigation.)

```
print('Copy and paste me to the codeblock!')
```

<iframe src="https://brainhack101.github.io/introML-book/01/MAIN_tutorial_intro_to_nilearn.html" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0"></iframe>

+++
@title[showhide]
#### @color[gray](You can show/hide codeblocks.)
![](assets/img/gif3.gif)

---

@snap[west span-50]
## @color[gray](How to create a Jupyter Book?)
@snapend

@snap[east span-50]
![](assets/img/jbook.png)
@snapend

@snap[south]
@fa[arrow-down fa-3x icon-color]
@snapend

+++
@title[howto]

#### @color[gray](Jupyter Books have two building blocks.)
![](assets/img/equals.png)

+++
@title[mdipynb]

@snap[north-west span-50]
#### @color[black](Markdown files)
![](assets/img/mdown.png)

@snap[text-left text-04]
Creating a Mardown is a piece of cake, yet Markdowns are powerful. For example, this whole presentation is created out of [a single Markdown file](https://github.com/agahkarakuzu/jnbkpitch/blob/master/PITCHME.md)! 
<br>
<br>
If you would like to learn how to create a Mardkown in 3 minutes, [visit this link](https://guides.github.com/features/mastering-markdown/).
@snapend


@snap[north-east span-50]
#### @color[orange](Jupyter Notebooks)
![](assets/img/ipynbook.png)

@snap[text-right text-04]
[Jupyter Notebooks](https://jupyter.org/) allows you to create and share documents that contain live code, equations, visualizations and narrative text. There are more than **40 programming languages** available to them! 
<br>
<br>
Here is your [quick starter guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/) for Jupyter Notebooks.
@snapend

@snapend

+++
@title[create]

@snap[north]
#### @color[Gray](You can create a Jupyter book in 3 lines)
@snapend

@snap[text-center text-05]
Open a terminal, and install Jupyter Book:
@snapend

```
pip install jupyter_book
```
@snap[text-center text-05]
Create a new book using the demo book content:
@snapend

```
jupyter-book create mybookname --demo
```
@snap[text-center text-05]
Now, build the markdown that Jekyll will use for your book. Run this command:
@snapend

```
jupyter-book build mybookname
```

@snap[text-center text-05]
You are all set! You can now either push your book to GitHub and serve the demo with gh-pages, or modify the book with your own content.
@snapend

@snap[south]
@css[tip3](This tutorial has been adopted from [Jupyter Book website](https://jupyter.org/jupyter-book/intro.html).)
@snapend

+++ 
@title[files]

@snap[north]
#### @color[Gray](Let's take a look at the files in the demo book)
@snapend

```
mybookname/
├── assets
│   └── custom
│       ├── custom.css
│       └── custom.js
├── _config.yml
├── content
│   ├── features
│   │  ├── features.md ---> This is a markdown file.
│   │  └── notebooks.ipynb ---> This is a Jupyter Notebook.
│   └── LICENSE.md
├── _data
│   └── toc.yml
└── requirements.txt
```

@snap[text-center text-06]
The content files are either `Jupyter Notebooks` or `Markdown files`. These are the files that define “pages” in your book.
@snapend

@snap[south]
@css[tip3](This tutorial has been adopted from [Jupyter Book website](https://jupyter.org/jupyter-book/intro.html).)
@snapend

---

@snap[west span-50]
# @color[gray](FAQ)
@fa[question-circle fa-5x icon-color2]
@snapend


+++ 
@title[questions]

@snap[north span-100]
@snap[text-left text-06 text-red]
@color[red](Can I start writing my paper in Jupyter Book?)
@snapend


@snap[text-left text-06 text-red text-italic]
In theory, you can. But in practice, Jupyter Book's ecosystem does not provide you with a tailored word processor. So, it may not be the most convenient way to start writing a paper from scratch. You can imagine Jupyter Book as medium where you bring different pieces together to create an open, interactive and reproducible publication. 
@snapend

<br>

@snap[text-left text-06]
@color[red](My work does not include any code. What value can Jupyter Books add to my workflow?) 
@snapend

<br>

@snap[text-left text-06 text-red]
@color[red](License?)
@snapend

<br>

@snap[text-left text-06 text-red]
@color[red](Citing?) 
@snapend

@snapend
