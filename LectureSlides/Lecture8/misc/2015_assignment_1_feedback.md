## Assignment 2 General Feedback (1)

- Please see me in my office hours to help refine operationalisation, research question, etc.

- Proofread your work!

    + Finish your sentences!

    + **Check output document** to see if it has rendered correctly.

- A catchy and descriptive title is good to have!

- If you use HTML make sure you provide a link to a hosted and rendered version, 
e.g. on [rawgit](https://rawgit.com/).

## Assignment 2 Feedback (2)

- Numbered section headings, in YAML header:

```
number_sections: true
```

## Assignment 2 Feedback (3)

Figure captions, in YAML header include: 

```
fig_caption: true
```

Then, in knitr head include option:

```
fig.cap = "A Caption Example"
```

or in imported images:

```
![A Caption Example \label{LaTeXref}](some_image.png)
```

Can reference in knitr LaTeX with `\ref{LaTeXRef}`.
