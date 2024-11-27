# LaTeX Documentation, Tutorials, Examples, and Resources

![LaTeX Image](/assets/tex.png)

This repository contains various LaTeX documents and resources for mathematical and scientific topics. It is organized into multiple directories, each focusing on different aspects of mathematics and LaTeX typesetting.

## Directory Structure

- **`2D Plot/`**: Examples of 2D plots created using TikZ and PGFPlots.
  - **`Cubic Function Plot with Labeled Points/`**: Plot of a cubic function with labeled points.
  - **`Highly Oscillatory Function Plot with Gridlines/`**: A plot of a highly oscillatory function with gridlines.
  - **`Integral Area/`**: Plot showing the area under a curve.
  - **`Leading Term/`**: Plot illustrating the leading term of a polynomial.
  - **`Positive Cosine Function/`**: Plot for positive functions.
  - **`Scatter Plot with Labeled Points and Gridlines/`**: Plot for scatter Plot with labeled points and gridlines.
  - **`Sine and Cosine/`**: Plots for sine and cosine.
  - **`The Existence of Derivatives/`**: Plots for the existence of derivatives.
- **`3D Plot/`**: Examples of 3D plots.
- **`assets/`**: Images and other assets used in the documents.
- **`Book Cover/`**: LaTeX files to create professional book covers.
- **`Drawing Angles in Tikz/`**: Examples of drawing angles using TikZ.
- **`Integrals/`**: Examples of integral calculations and visualizations.
- **`Math_Topics/`**: LaTeX documents on various mathematical topics.
- **`MCR3U - Functions University Notes/`**: My notes and examples for the MCR3U Functions course.
- **`MCV4U - Calculus and Vectors/`**: My notes and examples for the MCV4U Calculus and Vectors course.
- **`MHF4U - Advanced Functions/`**: My notes and examples for the MHF4U Advanced Functions course.
- **`Mirror/`**: Mirrored examples and documents.
- **`preamble.tex`**: Common LaTeX preamble settings and packages.
- **`README.md`**: This file.
- **`Trig Diagram/`**: Diagrams related to trigonometric functions.
- **`Typesetting maths example.tex`**: Example document demonstrating typesetting of mathematical expressions.
- **`Unit Circle/`**: Documents and visualizations related to the unit circle.
- **`Vectors/`**: Vector diagrams and calculations.
- **`Zip/`**: Zipped archives containing various documents and resources.

## Getting Started
To compile LaTeX documents, you first need to have a LaTeX distribution installed on your system. A LaTeX distribution provides the necessary tools and packages for compiling `.tex` files into PDF or other formats. Some popular LaTeX distributions include **TeX Live** (for Linux, macOS, and Windows), **MikTeX** (for Windows), and **MacTeX** (for macOS). These distributions include a variety of LaTeX packages that are necessary for compiling mathematical and scientific documents, as well as basic templates and examples.

Once you have a LaTeX distribution installed, you can use different tools or editors to write and compile your LaTeX documents. Below are some recommended tools:

- **TeXShop** (macOS): A free LaTeX editor specifically designed for macOS users. It integrates with MacTeX and provides a simple interface for compiling LaTeX documents.
  
- **TeXworks** (Windows, macOS, Linux): A lightweight LaTeX editor that is cross-platform and comes bundled with MikTeX or TeX Live distributions. It offers basic editing features and an easy way to compile documents.

- **Overleaf** (Web-based): A popular web-based LaTeX editor that allows you to write, compile, and share LaTeX documents directly from your browser. Overleaf provides real-time collaboration and is ideal for beginners or anyone who wants to get started quickly without installing software locally.

- **VS Code with LaTeX Workshop extension** (Windows, macOS, Linux): A more advanced text editor that can be enhanced with the LaTeX Workshop extension for features such as autocompletion, error checking, and document preview. This setup is ideal for more experienced LaTeX users who want a customizable editor.

After selecting your preferred tool, open the `.tex` file in the LaTeX editor and press the compile or build button to generate the final document. Typically, this will create a `.pdf` file, but you can also output other formats like `.dvi` or `.ps` depending on your settings and preferences. Most editors will automatically handle all necessary steps, including running the LaTeX engine and generating any auxiliary files (such as the `.aux` or `.log` files).

For large or complex documents, you may need to compile the document multiple times to ensure that all references, citations, and cross-references are correctly resolved.

By using any of these tools, you will be able to compile your LaTeX documents smoothly and generate professional-quality PDFs for academic, technical, or scientific purposes.


## Example Usage 
### Creating a Document
```tex
\documentclass{article}

\begin{document}

% Title of the document
\title{My First LaTeX Project}
\author{Kensukeken}

% Generate the title
\maketitle

\section{Introduction}

% Introduction section
This is the introduction to my first LaTeX project.

\section{Body}

% Main body of the document
This is the body of my first LaTeX project.

\subsection{Subsection}

% Subsection within the body
This is a subsection.

\subsubsection{Subsubsection}

% Subsubsection within the subsection
This is a subsubsection.

\section{Conclusion}

% Conclusion section
This is the conclusion of my first LaTeX project.
etc...

\end{document}
```
You can view the full file [here](./Getting%20Started%20With%20TeX.tex).

### Typesetting Math Example Usage
```tex
\documentclass{article}
\usepackage{amsmath} % for the equation* environment
\begin{document}

This is a simple math expression \(\sqrt{x^2+1}\) inside text. 
And this is also the same: 
\begin{math}
\sqrt{x^2+1}
\end{math}
but by using another command.

This is a simple math expression without numbering
\[\sqrt{x^2+1}\] 
separated from text.

This is also the same:
\begin{displaymath}
\sqrt{x^2+1}
\end{displaymath}

\ldots and this:
\begin{equation*}
\sqrt{x^2+1}
\end{equation*}

\end{document}
```
You can view the full file [here](./matrix%20multiplication%20example.tex).


# LaTeX & TeX Resources

Useful resources for learning and mastering LaTeX & TeX.

## LaTeX

### Tutorials

- [Overleaf's Tutorials](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes): Beginner-friendly tutorial covering the basics of LaTeX.
- [Overleaf Documentation](https://www.overleaf.com/learn): Comprehensive documentation on LaTeX usage.
- [Learn LaTeX](https://www.learnlatex.org/): Interactive tutorial to learn LaTeX step-by-step.

### Common Packages

- [amsmath & mathtools](https://ctan.org/pkg/amsmath) & [mathtools](https://ctan.org/pkg/mathtools): Essential packages for typesetting math equations.
- [amsthm & amssymb](https://ctan.org/pkg/amsthm) & [amssymb](https://ctan.org/pkg/amssymb): Packages for additional symbols and theorem environments.
- [PGF/TikZ](https://ctan.org/pkg/pgf): A powerful package for creating high-quality graphics and diagrams.
- [Effortless Plotting with PGFPlots](https://mirror.niser.ac.in/ctan/graphics/pgf/contrib/pgfplots/doc/pgfplots.pdf): A detailed guide to creating plots and charts with PGFPlots.

### Symbols

- [Detexify](http://detexify.kirelabs.org/classify.html): Interactive tool to find LaTeX commands for symbols.
- [TeXit's Cheatsheet](https://cdn.discordapp.com/attachments/554128715790155796/555351313836277781/texit_cheatsheet_1.pdf): Cheatsheet for common LaTeX symbols.
- [Math Symbols](https://www.caam.rice.edu/~heinken/latex/symbols.pdf): A comprehensive list of LaTeX commands for math symbols.
- [Comprehensive List of Symbols](http://tug.ctan.org/info/symbols/comprehensive/symbols-a4.pdf): Full list of LaTeX commands for various symbols.

### Additional Resources

- [Stack Exchange TeX](https://tex.stackexchange.com/): Community-driven Q&A site for LaTeX-related queries.

## TeX

### Guides

- [Notes On Programming in TeX](http://pgfplots.sourceforge.net/TeX-programming-notes.pdf): Guide to programming in TeX.
- [The TeXbook](https://cdn.discordapp.com/attachments/852438126651506728/1068824115059892304/texbook.pdf): Comprehensive introduction to TeX.
- [TeX by Topic](https://ctan.org/pkg/texbytopic): A guide covering advanced TeX topics.
- [A Gentle Introduction to TeX](https://ctan.org/pkg/gentle): Beginner-friendly introduction to TeX.
- [TeX in a Nutshell](http://petr.olsak.net/ftp/olsak/optex/tex-nutshell.pdf): Concise reference guide to TeX.
- [source2e](https://ctan.org/pkg/source2e): Source code of LaTeX2e's document class and packages.
---

## Contributing
To contribute to this project:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push your branch (`git push origin feature-branch`).
6. Open a pull request.

## Acknowledgement

I want to say thank you to these people and groups for their help and support:

- **Overleaf**: For giving a great platform and resources for LaTeX users.
- **TeX Stack Exchange Community**: For their ongoing help and sharing of knowledge.
- **CTAN (Comprehensive TeX Archive Network)**: For keeping a big collection of LaTeX packages and guides.


## Author

Kensukeken
