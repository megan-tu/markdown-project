# Markdown to HTML compiler

![command_line](https://github.com/megan-tu/markdown-project/actions/workflows/command_line.yaml/badge.svg)
![](https://github.com/megan-tu/markdown-compiler.git/workflows/flake8/badge.svg)&nbsp;
![flake8](https://github.com/megan-tu/markdown-project/actions/workflows/flake8.yaml/badge.svg)

A simple project for converting markdown files to HTML.

Basic usage:
```
$ markdown-compiler example/README.md
```

<img src='examples/example.png' width=300px>

Fancy CSS formatting can be included with the flag `--add_css`:
```
$ markdown-compiler example/README.md --add_css
```

<img src='examples/example-css.png' width=300px>
