# tufte-custom

Clean fork of the `tufte-latex` project.

`tufte-latex` has some weird `xelatex` interactions; this project is mainly for personal use, so I'm ensuring it works for *me* without addressing generalization problems.

## Getting started

```sh
export TEXINPUTS=/path/to/tufte-latex:$TEXINPUTS
```

For now, working with [pandoc-starter](github.com/jez/pandoc-starter) for parameter preprocessing and Makefile support. I may later add support for this project to `topdf`.
