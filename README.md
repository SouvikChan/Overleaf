# Overleaf
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Deedy - One Page Two Column Resume
% LaTeX Template
% Version 1.2 (16/9/2014)
%
% Original author:
% Debarghya Das (http://debarghyadas.com)
%
% Original repository:
% https://github.com/deedydas/Deedy-Resume
%
% IMPORTANT: THIS TEMPLATE NEEDS TO BE COMPILED WITH XeLaTeX
%
% This template uses several fonts not included with Windows/Linux by
% default. If you get compilation errors saying a font is missing, find the line
% on which the font is used and either change it to a font included with your
% operating system or comment the line out to use the default font.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% 
% TODO:
% 1. Integrate biber/bibtex for article citation under publications.
% 2. Figure out a smoother way for the document to flow onto the next page.
% 3. Add styling information for a "Projects/Hacks" section.
% 4. Add location/address information
% 5. Merge OpenFont and MacFonts as a single sty with options.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% CHANGELOG:
% v1.1:
% 1. Fixed several compilation bugs with \renewcommand
% 2. Got Open-source fonts (Windows/Linux support)
% 3. Added Last Updated
% 4. Move Title styling into .sty
% 5. Commented .sty file.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% Known Issues:
% 1. Overflows onto second page if any column's contents are more than the
% vertical limit
% 2. Hacky space on the first bullet point on the second column.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


\documentclass[]{deedy-resume-openfont}
\usepackage{fancyhdr}
 
\pagestyle{fancy}
\fancyhf{}
 
\begin{document}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     LAST UPDATED DATE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\lastupdated

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     TITLE NAME
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\namesection{Souvik}{Chandra}{ %\urlstyle{same}\href{http://debarghyadas.com}{debarghyadas.com}| \href{http://fb.co/dd}{fb.co/dd}\\
\href{mailto:deedy@fb.com}{https://github.com/SouvikChan} | 7584050718 | \href{mailto:dd367@cornell.edu}{souvikchandra9454@gmail.com}
}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN ONE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{minipage}[t]{0.33\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EDUCATION
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Education} 

\subsection{HOOGHLY ENGINEERING AND TECHNOLOGY COLLEGE}
\descript{\textbf{BTECH} in Computer Science}
\location{Expected,Dec 2024 | WEST BENGAL}
\location{ \textbf{GPA: 9.5 / 10.0}}
% \section{}
\subsection{SHEAKHALA BM HIGH SCHOOL}
\descript{HIGHER SECONDARY}
\location{August 2020 | Hooghly, West Bengal}\\
\location{ Aggregate \textbf{86.0} \\}
\sectionsep

\subsection{NILARPUR RM HIGH SCHOOL}
\descript{SECONDARY}
\location{August 2018 | Hooghly, West Bengal}\\
\location{ Aggregate \textbf{85.5} \\}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     LINKS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Links} 
% \subsection{}
\textbf{Leetcode:} \href{https://leetcode.com/SouvikChandra/}{\bf SouvikChandra} \\
\textbf{Github:} \href{https://github.com/SouvikChan}{\bf SouvikChan} \\
\textbf{LinkedIn:}  \href{https://www.linkedin.com/in/souvik-chandra-085a83214/}{\bf souvik-chandra} \\
\textbf{CodeForces:}  \href{https://codeforces.com/profile/SouvikCH}{\bf SouvikCH} \\
\textbf{CodeChef:} \href{https://www.codechef.com/users/souvikch30}{\bf souvikch30} \\
% Quora://  \href{https://www.quora.com/Debarghya-Das}{\bf Debarghya-Das}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     COURSEWORK
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Coursework}
\subsection{UNDERGRADUATE}

\textbf{Data Structures and Algorithms} \\
\textbf{Object-oriented Programming}  \\
\textbf{Operating System} \\
\textbf{Compilers + Practicum} \\
\textbf{Functional Programming} \\
\textbf{Computer Graphics}\\
\textbf{Computer Architecture}\\
\textbf{Machine Learning} \\
\sectionsep

% \subsection{Undergraduate}
% Information Retrieval \\
% Operating Systems \\
% Artificial Intelligence + Practicum \\
% Functional Programming \\
% Computer Graphics + Practicum \\
% {\footnotesize \textit{\textbf{(Research Asst. \& Teaching Asst 2x) }}} \\
% Unix Tools and Scripting \\

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     SKILLS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{\textbf{Programming Skills}}
% \subsection{}
\location{Languages:}
C \textbullet{}   \textbf{C++} \textbullet{} \textbf{Dart} \textbullet{} \textbf{Javascript} \\
% \textbullet{}  \textbullet{}  \textbullet{} \\ \\ 
\location{Technologies:}
Full Stack Web Development \textbullet{} \textbf{Android Development} \\
%\textbullet{} CSS \textbullet{} PHP \textbullet{} Assembly \\
\location{Frame Work and Library:}
\textbf{React js} \textbullet{} Node js \textbullet{} css \textbullet{} \textbf{Flutter} \textbullet{} TailWind css \textbullet{} javascript \textbullet{} Bootstarp \\
\location{Familiar:}
Git \textbullet{} Github \textbullet{} Heroku \textbullet{} Netlify 
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN TWO
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\end{minipage} 
\hfill
\begin{minipage}[t]{0.65\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EXPERIENCE
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{PROJECTS}
\subsection{}
\runsubsection{RESUME BUILDER APP}
\descript{\href{https://resume-builder-souvik.netlify.app/}{\bf |Live Link|} \href{https://github.com/SouvikChan/Resume-Builder-Using-React/}{\bf |Github Link|}}
\vspace{\topsep} % Hacky fix for awkward extra vertical space
\begin{tightemize}
\item A resume builder website using \textbf{react}, \textbf{material Ui}, \textbf{css} and \textbf{react hooks}.
\item It will build \textbf{real time resume} with different \textbf{color} and \textbf{styles}.
\item \textbf{Attach hyperlink} and lastly has the option to \textbf{download} the resume in \textbf{pdf format}.
\end{tightemize}
\sectionsep

\runsubsection{GRAMMARLY CLONE}
\descript{\href{https://souvikchan.github.io/Grammarly-Lite/}{\bf |Live Link|} \href{https://github.com/SouvikChan/Grammarly-Lite/}{\bf |Github Link|}}
\vspace{\topsep} % Hacky fix for awkward extra vertical space
\begin{tightemize}
\item A website like \textbf{grammarly} which \textbf{auto correct mistakes words and sentences}.
\item It has been build using \textbf{javascript} and \textbf{css}.
\item It has the option to \textbf{count the words} and \textbf{option to copy} the text.
\end{tightemize}
\sectionsep

% \runsubsection{Google}
% \descript{| Software Engineering Intern }
% \location{May 2013 ??? Aug 2013 | Mountain View, CA}
% \begin{tightemize}
% \item Worked on the YouTube Captions team, in Javascript and Python to plan, to design and develop the full stack to add and edit Automatic Speech Recognition captions. In production.
% \item Created a backbone.js-like framework for the Captions editor.
% \end{tightemize}
% \sectionsep

\section{EXPERIENCE}
\subsection{}
\runsubsection{DIGITAL OCEAN}
\descript{| Open Source Contributor }
\location{Oct 2021 ??? Nov 2021}
\begin{tightemize}
\item Completed \textbf{Hacktober-Fest} sponsored by digital ocean twice both in 2020 and 2021.
\item Contributed to \textbf{2} of their \textbf{open source projects}.
\item Fixed some bugs related to components and added some animation into it.
\end{tightemize}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     RESEARCH
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

% \section{Research}
% \runsubsection{Cornell Robot Learning Lab}
% \descript{| Researcher}
% \location{Jan 2014 ??? Jan 2015 | Ithaca, NY}
% Worked with \textbf{\href{http://www.cs.cornell.edu/~ashesh/}{Ashesh Jain}} and \textbf{\href{http://www.cs.cornell.edu/~asaxena/}{Prof Ashutosh Saxena}} to create \textbf{PlanIt}, a tool which  learns from large scale user preference feedback to plan robot trajectories in human environments.  
% \sectionsep
% {Experience}
% \runsubsection{Cornell Phonetics Lab}
% \descript{| Head Undergraduate Researcher}
% \location{Mar 2012 ??? May 2013 | Ithaca, NY}
% Led the development of \textbf{QuickTongue}, the first ever breakthrough tongue-controlled game with \textbf{\href{http://conf.ling.cornell.edu/~tilsen/}{Prof Sam Tilsen}} to aid in Linguistics research. 
% \sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     AWARDS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{ACHIEVEMENTS} 
\subsection{}
% \sectionsep
\begin{tabular}{rll}
\sectionsep
2022   & Solved over\textbf{ 1000 problems} on \textbf{Leetcode} and \textbf{Codechef} and \textbf{Codeforces}\\
\sectionsep
\subsection{}
2022	     & Got \textbf{628 global rank} on codeforces round div 2 among \textbf{20000} participants \\
\sectionsep
\subsection{}
2022	     & \textbf{Specialist} on \textbf{Codeforces} with max rating of \textbf{1500}\\
\sectionsep
\subsection{}
2022	     & \textbf{4 star} on\textbf{ Codechef} with max rating of \textbf{1848}\\
\sectionsep
\subsection{}
2022     & \textbf{7113th} Global Rank \textbf{Google kickstart} 2022 Round A \\
\sectionsep
\subsection{}
2022     & Attended \textbf{over 100+} contest on \textbf{Leetcode} and \textbf{Codechef} and \textbf{Codeforces} \\
\subsection{}
2011     & Rank 1/300 Tech-HETC-Coding-Competition\\
\end{tabular}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     PUBLICATIONS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{CERTIFICATES}
\subsection{}
\begin{tightemize}
\item \href{https://www.udemy.com/certificate/UC-6b05c16a-9c18-4bdb-ac7d-1bcf79a45f37/}{\bf Udemy Machine Learning and Deep Learning Basics}
\item\href{https://courses.edx.org/certificates/daf6dede6caa46788a9624207c3aadbd/}{\bf Python Basics and It's applications}
\item\href{https://codingcompetitions.withgoogle.com/kickstart/certificate/summary/00000000008caba4/}{\bf Qualified Google Kickstart Round A}
\end{tightemize}
% \section{Publications} 
% \renewcommand\refname{\vskip -1.5em} % Couldn't get this working from the .cls file
% \bibliographystyle{abbrv}
% \bibliography{publications}
% \nocite{*}

\end{minipage} 
\end{document}  \documentclass[]{article}
