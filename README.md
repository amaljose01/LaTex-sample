# README

## About

This is a sample LaTeX document that can be edited using Overleaf. It demonstrates the basic structure and functionality of LaTeX for creating professional documents.

A copy of this code can be found at the following Overleaf project link:
[Overleaf Project Link](https://www.overleaf.com/project/6777b4dc5f06ac44af89315d)

Additionally, a sample PDF has been uploaded for reference to help you understand how the document appears when compiled.

## Default Font

The default font used in the provided LaTeX document is **Computer Modern**, the standard font family in most LaTeX document classes. This font was designed by Donald Knuth and is recognized for its elegant and professional appearance.

## Changing the Font

If you wish to change the default font, you can use the following packages:

### Times New Roman
To use Times New Roman, include the `times` package in your LaTeX document:

```latex
\usepackage{times} % Times New Roman
```

### Times Roman with Matching Math Symbols
To use Times Roman with matching mathematical symbols, use the `mathptmx` package:

```latex
\usepackage{mathptmx}
```

### Custom Fonts with XeLaTeX or LuaLaTeX
If you are using XeLaTeX or LuaLaTeX, you can specify a custom font with the `fontspec` package. For example:

```latex
\usepackage{fontspec}
\setmainfont{Times New Roman} % Replace with your desired font
```

## Feedback

If you encounter any issues or have suggestions for improving this document, feel free to update the code or share feedback. Happy LaTeXing!

