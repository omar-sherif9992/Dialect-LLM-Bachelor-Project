\documentclass{article} % beamer for presentations
\usepackage{graphicx} % Required for inserting images
\usepackage{amsmath,amsfonts,amssymb}
\usepackage{esint}
\usepackage{tcolorbox}
\title{learning}
\author{omar sherif}
\date{\today}






\begin{document}

\tableofcontents

\maketitle

\section{Basic text manipulation}
\subsection{Bold Face}
\textbf{bold}
\textit{italicized}
\textbf{\textit{\underline{woow}}}

\section{Basic syntax for formulas}
\subsection{inline formulas}
quadratic function $\frac{-b \pm \sqrt{b^2-4ac}}{2a}$

\subsection{Display style formula}
$$ e^{i\pi}+1=0$$

\section{Calculus Notation}
\subsection{integration}
\begin{enumerate}
    \item $\int_{a}^{b} \sin{\theta}\ d\theta$
    \item $$ \iint{\cos{\theta}\cdot 2}$$
    \item 
\end{enumerate}

\begin{itemize}
    \item aaa
\end{itemize}

\section{matrix}
\subsection(vectors)
\subsubsection{ha}

$$\vec{v} = \langle v_1$$

$e^{i\pi}+1=0$

$ (1+\frac{1}{n})$


\section{pics}
\begin{figure}
    \centering
    \includegraphics{}
    \caption{Caption}
    \label{fig:my_label}
\end{figure}



\begin{tcolorbox}
ssa
\end{tcolorbox}


\begin{tabular}{ |p{3cm}||p{3cm}|p{3cm}|p{3cm}|  }
 \hline
 \multicolumn{4}{|c|}{Country List} \\
 \hline
 Country Name     or Area Name& ISO ALPHA 2 Code &ISO ALPHA 3 Code&ISO numeric Code\\
 \hline
 Afghanistan   & AF    &AFG&   004\\
 Aland Islands&   AX  & ALA   &248\\
 Albania &AL & ALB&  008\\
 Algeria    &DZ & DZA&  012\\
 American Samoa&   AS  & ASM&016\\
 Andorra& AD  & AND   &020\\
 Angola& AO  & AGO&024\\
 \hline
\end{tabular}

\end{document}

