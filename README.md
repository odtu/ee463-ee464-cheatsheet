# EE463-EE464 Cheat Sheet

This repo holds the [LaTeX](https://www.latex-project.org/) document that you will use as a cheatsheet in the exam.
You are free to modify the cheatsheet as you wish, and all students are encouraged to contribute. 

There is a single branch (`master`) and one cheat sheet per course:

| Course | Source | Last compiled output |
| --- | --- | --- |
| EE463 | [`ee463/cheatsheet.tex`](ee463/cheatsheet.tex) | [`ee463/cheatsheet.pdf`](ee463/cheatsheet.pdf) |
| EE464 | [`ee464/cheatsheet.tex`](ee464/cheatsheet.tex) | [`ee464/cheatsheet.pdf`](ee464/cheatsheet.pdf) |

Here are a few rules:

- All students will use the same cheat sheet. No other documents will be allowed.
- Cheat sheet will be one page (single side) A-4 document.
- The latest version of the course's .tex file in the `master` branch will be compiled at **TBA**, and the first page of the PDF output will be distributed in the exam. 

A few hints:

- Be careful when editing the .tex file if you don't know how to use LaTeX.
- If there is a specific equation you want to include, it may be better to ask your friends to do it by opening [a new issue](https://github.com/odtu/ee463-ee464-cheatsheet/issues/new).
- Actually, all the equations I presented in my slides are written with LaTeX, so you can directly copy them to your cheat-sheet. In order to do that, either go to the files [in my GitHub repo](https://github.com/ozank/ozank.github.io/tree/master/presentations), or open a .html presentation and view source (i.e. click Ctrl+U).
- You are also free to add images, but it can be tricky to compile them using an online compiler.
- **If you add an image, commit the image file next to the .tex file in the same pull request.** If you edit on Overleaf, push the images too, otherwise the cheat sheet will not compile for anyone else.
- Here are a few links to let you compile .tex files online, alternatively you can install a local [LaTeX compiler](https://www.tug.org/begin.html).
    - [Overleaf](https://www.overleaf.com/) (probably the best option)
    - [Authorea](https://www.authorea.com/) (Another online compiler)
    - [Online compiler](http://manuels.github.io/texlive.js)
    - [Quick equation compiler](http://www.hostmath.com/)
    - [From drawing to LaTeX](http://detexify.kirelabs.org/classify.html)
    - [LaTeX Cloud Compiler](https://latexonline.cc/)

- If you have any problems, Google is your friend.

## Previous versions

- [`ee463/2025-26-final.pdf`](ee463/2025-26-final.pdf): the sheet used in the 2025-26 EE463 final (edited directly as a PDF, there is no .tex source for its extra content).
- Older sheets are kept as git tags: `archive/ee463-final-2018` and `archive/ee463-mt1-2023`.
