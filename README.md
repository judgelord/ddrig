<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Hey fellow polisci grads! APSA will soon open 2021 NSF <a href="https://twitter.com/hashtag/DDRIG?src=hash&amp;ref_src=twsrc%5Etfw">#DDRIG</a> applications. 👀<br><br>To help get you started, I made a template (bookdown/LaTeX/Docx) based on last year&#39;s call: <a href="https://judgelord.github.io/ddrig">https://judgelord.github.io/ddrig</a><br><br>Please share far and wide! And good luck! <br><br> - Devin Judge-Lord (@JudgeLord) <a href="https://twitter.com/JudgeLord/status/1377712461697052673?ref_src=twsrc%5Etfw">April 1, 2021</a></blockquote> 

Fork and clone this repository to build a gitbook site for your DDRIG application with the [`bookdown`](https://bookdown.org/) package for R.  (Or download just the [.docx](https://judgelord.github.io/ddrig/app.docx) or [.tex](https://judgelord.github.io/ddrig/app.tex) template if you don't use bookdown.)

If you opt to [publish](https://github.blog/2016-08-17-simpler-github-pages-publishing/) your new /ddrig repository, your friends and advisors will be able to read your draft proposal as a mobile-friendly web page or download it as a .docx or .pdf on a webpage that looks like <https://judgelord.github.io/ddrig>.

---

The `/assets` folder contains some key tools:

- `apsr.bst` formats your citations
- LaTeX is formatted with `article-template.tex` adapted from https://github.com/svmiller/svm-r-markdown-templates
- `clean-bib.R` removes any problematic special characters from a .bib file (e.g., one exported from Mendeley or Zotero)

`/docs` is where the .html, .pdf, and .docx output will appear

`/figs` is where to put figures you want to include