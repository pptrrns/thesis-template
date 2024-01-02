### List of useful commands 

###### `itam-thesis ~ cheatsheet` 



##### Section formatting

````latex
\part{Your Part Title}
\chapter{Your Chapter Title}
\section{Your Section Title}
\subsection{Your Subsection Title}
\subsubsection{Your Subsubsection Title}
\paragraph{Your Paragraph Title}
\subparagraph{Your Subparagraph Title}
````

##### Text size

````latex
\Huge
\huge
\LARGE
\Large
\large
\normalsize
\small
\footnotesize
\scriptsize
\tiny
````

##### Font shapes

```latex
\emph{} % This is Italic Shape
\scshape{} % This is Small Caps Shape
```

##### New thought block

```latex
\newthought{Your new thought here}
```

##### Analytical Index entries

````latex
\analyticentry{Your Index Term 1}
\analytics{Your Index Term 1}
````

##### Label and References

```latex
\hyperref[tab:figura1]{Figura \ref{fig:figura1}}

\label{tab:tabla1} % Table reference
\label{apendiceA} % Appendices references
\label{introduction} % Chapter reference
```

##### Center environment

```latex
\begin{center}
  Your centered content goes here
\end{center}
```

##### Itemize and enumerate environments

````latex
\begin{itemize}
  \item Your item 1
  \item Your item 2
\end{itemize}

\begin{enumerate}
  \item Your item 1
  \item Your item 2
\end{enumerate}
````

##### Quote Environment

`````latex
\begin{quote}
  \lipsum[2]
\end{quote}
`````

##### Savequote environment

````latex
\begin{savequote}[85mm]
  \small{Your quote here.}
  \qauthor{Your Author}
\end{savequote}
````

##### Equation Environment

````latex
\begin{equation}
x = 1
\end{equation}
````

##### Figure Environment

````latex
% Figure Environment

\begin{figure}[H]
    \centering 
        \includegraphics[width = \textwidth]{figures/fig#}
        \caption[Lorem Ipsum]{Proin at eros...
    \label{fig:figura#}}
\end{figure}

% Full page figure Environment

\newpage
\thispagestyle{empty}
\begin{landscape}
\thispagestyle{empty}
  \begin{figure}[p]
    \centering
    \includegraphics[width = \linewidth, keepaspectratio]{figures/fig#.png}
    \caption[Lorem Ipsum]{Proin at eros...}
    \label{fig:figura#}
  \end{figure}
\end{landscape}
````

##### Code Listing Environment

````latex
\begin{lstlisting}[language = R, caption = Lorem Ipsum]
  Lorem Ipsum
\end{lstlisting}
````

##### Footnotes

````latex
\footnote{Lorem ipsum.}\textsuperscript{,}\footnote{Lorem ipsum.}

\footnote{\lipsum[8]}
````

##### References

````latex
% The references.bib file contains the references. By default, the references are cited in the APSA style. 
% Use the command \citep{} to manage the references.

\citep{BibTeX key, BibTeX key}

\citep[pg.~32]{BibTeX key}

\citep{BibTeX key}

\citep[\emph{véase}][pg.~5]{BibTeX key}

\citep[Chap.~5]{BibTeX key}
````

##### Page settings


````latex
\blankpage % Add a blank page
\newpage % Add a new page
````
