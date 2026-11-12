#LaTeX


A collection of important LaTeX concepts and code examples learned during the Technical Writing course.

## 1. Introduction to LaTeX

LaTeX is a document preparation system used for creating professional academic and technical documents. It is especially useful for mathematical equations, tables, figures and structured writing.

## 2. Basic Document Structure

Every LaTeX document has a document class, a preamble and a document body.

```latex
\documentclass[12pt]{article}

\usepackage{amsmath}
\usepackage{xcolor}
\usepackage{graphicx}

\begin{document}

Hello World! This is my first LaTeX document.

\end{document}
```

**Important commands:**
- `\documentclass{article}` – Defines document type.
- `\usepackage{}` – Includes additional packages.
- `\begin{document}` – Starts document content.
- `\end{document}` – Ends document content.

## 3. Document Formatting

### Title and Sections

```latex
\title{Introduction to LaTeX}
\author{Your Name}
\date{\today}

\begin{document}

\maketitle

\section{Introduction}
\subsection{Features}
\subsubsection{Applications}

\end{document}
```

### Text Formatting

```latex
\textbf{Bold Text}

\textit{Italic Text}

\underline{Underlined Text}

\emph{Emphasized Text}
```

### Lists

**Bulleted list:**

```latex
\begin{itemize}
    \item C++
    \item Java
    \item Python
\end{itemize}
```

**Numbered list:**

```latex
\begin{enumerate}
    \item Introduction
    \item Implementation
    \item Conclusion
\end{enumerate}
```

## 4. Mathematical Expressions

LaTeX provides powerful features for writing mathematical expressions.

### Inline and Display Equations

```latex
Inline: \(x^2 + y^2 = z^2\)

\[
x^2 + y^2 = z^2
\]
```

### Fractions, Roots and Summations

```latex
\[
\frac{a+b}{c}
\qquad
\sqrt{x}
\qquad
\sum_{i=1}^{n} i
\qquad
\int_0^1 x^2\,dx
\]
```

### Aligned Equations

```latex
\begin{align*}
2x - 5y &= 8 \\
3x + 9y &= -12
\end{align*}
```

## 5. Arrays and Matrices

### Piecewise Function

```latex
\[
f(x)=
\begin{cases}
-x, & x<0 \\
0, & x=0 \\
x^2, & x>0
\end{cases}
\]
```

### Matrix

```latex
\[
A=
\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}
\]
```

Common matrix environments:

| Environment | Brackets |
|---|---|
| `matrix` | None |
| `pmatrix` | Parentheses |
| `bmatrix` | Square brackets |
| `Bmatrix` | Curly brackets |
| `vmatrix` | Vertical bars |

## 6. Tables

The `tabular` environment is used to create tables.

```latex
\begin{center}
\begin{tabular}{|c|c|c|}
\hline
Name & Subject & Marks \\
\hline
Alice & Maths & 90 \\
Bob & Physics & 85 \\
\hline
\end{tabular}
\end{center}
```

**Important commands:**
- `&` – Separates columns.
- `\\` – Ends a row.
- `\hline` – Adds a horizontal line.
- `\multicolumn{}` – Combines columns.
- `\multirow{}` – Combines rows (requires the `multirow` package).

## 7. Colours and Images

### Colours

Use the `xcolor` package.

```latex
\usepackage{xcolor}

\textcolor{red}{Red Text}

\definecolor{myblue}{RGB}{10,60,200}
\textcolor{myblue}{Custom Blue}

\colorbox{yellow}{Highlighted Text}
```

### Images

Use the `graphicx` package.

```latex
\usepackage{graphicx}

\begin{figure}[h]
    \centering
    \includegraphics[width=0.5\textwidth]{image.jpg}
    \caption{Sample Image}
    \label{fig:sample}
\end{figure}
```

## 8. Picture Environment

The `picture` environment allows simple drawings using coordinates.

```latex
\setlength{\unitlength}{1cm}

\begin{picture}(5,3)
    \put(1,1){\circle{1}}
    \put(3,1){\vector(1,0){1}}
    \put(2,2){\makebox(0,0){Point}}
\end{picture}
```

## 9. References and Bibliography

### Cross-References

```latex
\section{Introduction}
\label{sec:intro}

See Section~\ref{sec:intro}.
```

### Bibliography

```latex
This topic is explained in \cite{lamport}.

\begin{thebibliography}{9}
\bibitem{lamport}
Leslie Lamport,
LaTeX: A Document Preparation System.
\end{thebibliography}
```

## 10. Compilation

Save the LaTeX source file with the `.tex` extension.

Compile using:

```bash
pdflatex filename.tex
```

Some references and bibliographies may require multiple compilation passes.

## 11. Key Takeaways

Through this module, I learned:

- Basic LaTeX document structure and formatting.
- Creating lists and organising sections.
- Writing mathematical expressions and equations.
- Creating arrays, matrices and tables.
- Adding colours and images.
- Drawing simple objects using the picture environment.
- Managing references and bibliography.


