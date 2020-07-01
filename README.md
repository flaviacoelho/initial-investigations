# Initial Investigations on Refactorings and Modern Code Review


*This work was supervisioned by Prof. Tiago Massoni and Prof. Everton Alves<br>*
*Federal University of Campina Grande, Brazil</font><br>*
<img src="/img/splab.png" alt="SPLab Logo" width="17%" height="17%">
<hr>


<p>\begin{table}[h]
\begin{center}
\begin{tabular}{c|l|c|l}
\hline
\textit{\textbf{\small{Phase}}} &amp; \textit{\textbf{\small{Rationale}}} &amp; \textit{\textbf{\small{Result}}} &amp; \textit{\textbf{\small{Impact for the research}}}\
\hline \hline
\small{1} &amp;
\begin{tabular}[l]{@{}l@{}}
\small{Find an accurate refactoring} \
\small{detection tool for source code} \
\small{written in the Java language}
\end{tabular} &amp;
\small{RefactoringMiner} \cite{RefactoringMiner} &amp;
\begin{tabular}[l]{@{}l@{}}
\small{Knowledge on the}\
\small{state-of-the-art in}\
\small{refactoring detection}\
\end{tabular}\
\hline
\small{2} &amp;
\begin{tabular}[l]{@{}l@{}}
\small{Check the RefactoringMiner} \
\small{accuracy in detection of } \
\small{multiple refactorings in a}\
\small{single commit}
\end{tabular} &amp;
\small{Affirmative} &amp;
\begin{tabular}[l]{@{}l@{}}
\small{Selection of the} \
\small{RefactoringMiner for}\
\small{the purpose of}\
\small{refactoring detection}\
\end{tabular}\
\hline
\small{3} &amp;
\begin{tabular}[l]{@{}l@{}}
\small{Search for refactoring-aware} \
\small{solutions to support MCR}
\end{tabular} &amp;
\small{Systematic mapping} &amp;
\begin{tabular}[l]{@{}l@{}}
\small{A few potential} \
\small{research directions}\
\end{tabular}\
\hline
\small{4} &amp;
\begin{tabular}[l]{@{}l@{}}
\small{Verify the feasibility of an} \
\small{experiment about refactoring} \
\small{-aware code review in a} \
\small{midsize project}
\end{tabular} &amp;
\small{Infeasible} &amp;
\begin{tabular}[l]{@{}l@{}}
\small{Selection of Gerrit} \
\small{for an in-depth}\
\small{exploration}\
\end{tabular}\
\hline
\small{5} &amp;
\begin{tabular}[l]{@{}l@{}}
\small{Investigate a case study}\
\small{feasibility from Gerrit}\
\small{review data}\
\end{tabular} &amp;
\small{Brief &quot;case history&quot;} &amp;
\begin{tabular}[l]{@{}l@{}}
\small{Motivating results}\
\end{tabular}\
\hline</p>
<pre><code>        \small{6} &amp; 
            \begin{tabular}[l]{@{}l@{}} 
                 \small{Investigate a case study} \\
                 \small{feasibility from GitHub}\\
                 \small{open pull requests}\\
            \end{tabular} &amp; 
                \small{Brief &quot;case history&quot;} &amp;
                    \begin{tabular}[l]{@{}l@{}} 
                         \small{Motivating results} \\
                         \small{towards a case study}\\ 
                         \small{on merged pull} \\
                         \small{requests}\\ 
                    \end{tabular}\\
        \hline
        \small{7} &amp;
            \begin{tabular}[l]{@{}l@{}} 
                 \small{Investigate a case study} \\
                 \small{feasibility from GitHub} \\
                 \small{merged pull requests}\\
            \end{tabular} &amp; 
                \small{Brief &quot;case history&quot;} &amp;
                    \begin{tabular}[l]{@{}l@{}} 
                         \small{Decision for }\\
                         \small{performing a case study}\\ 
                         \small{on data from GitHub}\\ 
                         \small{merged pull requests}\\ 
                    \end{tabular}\\
        \hline
\end{tabular}
\end{center}
\caption{A summary of the preliminary investigation results}
\label{tab:summary}
</code></pre>
<p>\end{table}</p>
