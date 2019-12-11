  <html> 
 
</p> 
  <H2> Book suggestions</H2> 
<font size="2.6px">
pdf: <br />
rotate:<a href="http://www.pdfaid.com/rotate-pdf-pages-online.aspx">rotate:http://www.pdfaid.com/rotate-pdf-pages-online.aspx</a><br />
deletepages:<a href="https://pdfresizer.com/delete-pages">deletepages:https://pdfresizer.com/delete-pages</a><br />
1*2print:<a href="https://pdfresizer.com/optimize">1*2print:https://pdfresizer.com/optimize</a><br />
Sejdacrop:<a href="https://www.sejda.com/crop-pdf">Sejdacrop:https://www.sejda.com/crop-pdf</a><br />
%Sejdadeletepages:<a href="https://www.sejda.com/delete-pdf-pages">%Sejdadeletepages:https://www.sejda.com/delete-pdf-pages</a><br />
pdfcalendar:<a href="https://www.timeanddate.com/calendar/create.html">pdfcalendar:https://www.timeanddate.com/calendar/create.html</a><br />
 </p>
 onlinelatex: <br />
Roger'seqn:<a href="http://rogercortesi.com/eqn/">Roger'seqn:http://rogercortesi.com/eqn/</a><br />
Fulllatexcompile:<a href="http://latex.informatik.uni-halle.de/latex-online/latex.php">Fulllatexcompile:http://latex.informatik.uni-halle.de/latex-online/latex.php</a><br />
Latexmathsymbols..<a href="http://web.ift.uib.no/Teori/KURS/WRK/TeX/symALL.html">Latexmathsymbols..http://web.ift.uib.no/Teori/KURS/WRK/TeX/symALL.html</a><br />
xymatrixforcomm.diag.:<a href="http://www.jmilne.org/not/Mxymatrix.pdf">xymatrixforcomm.diag.:http://www.jmilne.org/not/Mxymatrix.pdf</a><br />
tikzcdcomm.diag.:<a href="https://tikzcd.yichuanshen.de/">tikzcdcomm.diag.:https://tikzcd.yichuanshen.de/</a><br />

 </p>


preambles..
 
\documentclass[12pt]{amsart}
\usepackage{amsthm, amsmath, amssymb,  amsfonts}
\usepackage{mathrsfs, enumitem, svn, stmaryrd, mathtools}
\usepackage{verbatim, comment} %for comment environ

%\usepackage{amsrefs}
%\usepackage{pxfonts}

%to cut margin
\usepackage[a4paper,bindingoffset=0.2in,left=1in,right=1in,top=1in,bottom=1in, footskip=.25in]{geometry}  

%\usepackage[a4paper,bindingoffset=0.2in, left=0.5in,right=0.5in,top=0.4in,bottom=0.4in, footskip=.25in]{geometry}


%%TABLES and DIAGRAMS
\usepackage{tabu} %for math mode of tables
 \usepackage{geometry}
\usepackage[table]{xcolor}
\usepackage{adjustbox}
\usepackage[all, cmtip]{xy}
%\parindent= 0pt
\parskip=2pt


%%LABELS and COLORS
% \usepackage[notref,notcite]{showkeys}  %shows all labels in your pdf
 %% Remember, label less than 10 letters, no signs

\usepackage{color}
\definecolor{ghcolor}{RGB}{0, 150, 200} %defines colors if you need in hyperref
\definecolor{winestain}{rgb}{0.5,0,0}
\usepackage[linktocpage=true, hidelinks, colorlinks, linkcolor=blue, citecolor=red, bookmarksopen=true]{hyperref} %linktocpage makes pages in toc clickable
%\RequirePackage{color}
%\definecolor{bwgreen}{rgb}{0.183,1,0.5}
%\definecolor{bwmagenta}{rgb}{0.7,0.0,0.1}
%\definecolor{bwblue}{rgb}{0.317,0.161,1}

%%%THEOREM styles (always small font)
\newtheorem{sublemma}{Sub-lemma}
\newtheorem{theorem}[subsubsection]{Theorem}
\newtheorem{thm}[subsubsection]{Theorem}
\newtheorem{lemma}[subsubsection]{Lemma}
\newtheorem{lem}[subsubsection]{Lemma}
\newtheorem{cor}[subsubsection]{Corollary}
\newtheorem{corollary}[subsubsection]{Corollary}
\newtheorem{conj}[subsubsection]{Conjecture}
\newtheorem{prop}[subsubsection]{Proposition}

\theoremstyle{definition}
\newtheorem{defn}[subsubsection]{Definition}
\newtheorem{construction}[subsubsection]{Construction}
\newtheorem{definition}[subsubsection]{Definition}
\newtheorem{example}[subsubsection]{Example}
\newtheorem{assumption}[subsubsection]{Assumption}
\newtheorem{question}[subsubsection]{Question}
\newtheorem{notation}[subsubsection]{Notation}
\newtheorem{Notation}[subsubsection]{Notation}

\newtheorem{convention}[subsubsection]{Convention}

\theoremstyle{remark}
\newtheorem{remark}[subsubsection]{Remark}
\newtheorem{rem}[subsubsection]{Remark}
%%NUMBERING
\numberwithin{equation}{subsection}
\setcounter{tocdepth}{2}

%%Macros. newcommand=fancier def; mathrm=math ver of textnormal;
%%ARROWS
\def \inj {\hookrightarrow }
\def \to {\rightarrow}
\def \onto {\twoheadrightarrow}
\renewcommand{\projlim}{\varprojlim}
%\DeclareMathOperator{\lim}{lim}
%%Matrix
\DeclareMathOperator{\Id}{Id}
\DeclareMathOperator{\diag}{diag}
\newcommand{\tr}{\operatorname*{tr}}
\newcommand{\GL}{\mathrm{GL}}
\DeclareMathOperator{\PGL}{PGL}
\DeclareMathOperator{\SL}{SL}
\DeclareMathOperator{\SO}{SO}
\DeclareMathOperator{\Spin}{Spin}
\newcommand{\End}{\mathrm{End}}
\def\Mat{\mathrm{Mat}}
\def\mat{\mathrm{Mat}}

\def \Md {{\mathrm M}_d}
\newcommand{\col}{\mathrm{col}}
\newcommand{\row}{\mathrm{row}}
%%Rings, modules, representations
\def\val{\mathrm val}
\DeclareMathOperator{\Ind}{Ind}
\DeclareMathOperator{\rank}{rank}
\DeclareMathOperator{\Mod}{Mod}
\newcommand{\tor}{\mathrm{tor}}
\newcommand{\fr}{\mathrm{fr}}
\DeclareMathOperator{\Rep}{Rep}
\DeclareMathOperator{\Sym}{Sym}
\DeclareMathOperator{\Hom}{Hom}
\DeclareMathOperator{\Ext}{Ext}
\DeclareMathOperator{\Tor}{Tor}
\DeclareMathOperator{\Ker}{ker}
\DeclareMathOperator{\im}{im}
\DeclareMathOperator{\coker}{coker}
\DeclareMathOperator{\Coker}{Coker}
\DeclareMathOperator{\Gal}{Gal}
\DeclareMathOperator{\gal}{Gal}
\DeclareMathOperator{\Res}{Res}
\DeclareMathOperator{\Proj}{Proj}
\def\cont{\mathrm{cont}}
\def\inf{\mathrm{inf}}
\def\sup{\mathrm{sup}}
\DeclareMathOperator{\Max}{Max}
\DeclareMathOperator{\disc}{disc}
\DeclareMathOperator{\Frac}{Frac}
\DeclareMathOperator{\Fr}{Fr}
\renewcommand{\Im}{\textnormal{Im}}
%%Filtration
\DeclareMathOperator{\Fil}{Fil}
\DeclareMathOperator{\gr}{gr}
\DeclareMathOperator{\Gr}{Gr}
%Geometry
\DeclareMathOperator{\Spa}{Spa}
\DeclareMathOperator{\Spd}{Spd}
\DeclareMathOperator{\Spec}{Spec}
\DeclareMathOperator{\Spf}{Spf}
\DeclareMathOperator{\Spm}{Spm}
\DeclareMathOperator{\Sp}{Sp}
\def\ad{\mathrm{ad}}
\def\an{\mathrm{an}}
\def\can{\mathrm{can}}
\def\et{\mathrm{\acute{e}t}}
\def\proet{\mathrm{pro\acute{e}t}}
\def\profet{\mathrm{prof\acute{e}t}}
\def\proket{\mathrm{prok\acute{e}t}}
\def\alg{\mathrm alg}
\def\geo{\mathrm geo}
\def\geom{\mathrm geom}
%%p-adic Hodge
\def\cris{\mathrm{cris}}
\newcommand{\st}{\mathrm{st}}
\def\pst{\mathrm{pst}}
\def\dR{\mathrm{dR}}
\def\HT{\mathrm{HT}}
\def\cycl{\mathrm{cycl}}
\def\Sen{\mathrm{Sen}}
\def\dif{\mathrm{dif}}
\def\rig{\mathrm{rig}}
\def\ord{\mathrm{ord}}

\DeclareMathOperator{\WD}{WD}
\newcommand{\frob}{\mathrm{frob}}
\newcommand{\Frob}{\mathrm{Frob}}
\newcommand{\nr}{\mathrm{nr}}
\newcommand{\unr}{\mathrm{unr}}
\newcommand{\un}{\mathrm{un}}
\newcommand{\ur}{\mathrm{ur}}
\newcommand{\sep}{\mathrm{sep}}
%%p-adic Hodge phi tau and loc ana vector
\newcommand{\Kpinfty}{K_{p^\infty}}
\newcommand{\Kinfty}{K_{\infty}}
\newcommand{\pa}{\mathrm{pa}}
\newcommand{\la}{\mathrm{la}}
\newcommand{\dan}{\text{$\mbox{-}\mathrm{an}$}}
\newcommand{\dla}{\text{$\mbox{-}\mathrm{la}$}}
\newcommand{\dpa}{\text{$\mbox{-}\mathrm{pa}$}}
%\renewcommand{\log}{\mathrm{log}}

%% CATEGORY
\newcommand{\MF}{\mathrm{MF}^{\varphi, N}_{K_0}}
\newcommand{\MFwa}{\mathrm{MF}^{\varphi, N, \mathrm{wa}}_{K_0}}
\newcommand{\bigMF}{\mathrm{MF}^{\varphi, N}_{S_{K_0}}}
\newcommand{\bigMFwa}{\mathrm{MF}^{\varphi, N, \mathrm{wa}}_{S_{K_0}}}
\newcommand{\ModhuaS}{\Mod_{\huaS}^{\varphi}}
\newcommand{\Mdual}{\huaM^{\vee}}
%% p-adic Hodge PERIOD RING
\newcommand{\ainf}{\mathbf{A}_{\mathrm{inf}}}
\newcommand{\acris}{\mathbf{A}_{\mathrm{cris}}}
\newcommand{\bcris}{\mathbf{B}_{\mathrm{cris}}}
\newcommand{\Acris}{\mathbf{A}_{\mathrm{cris}}}
\newcommand{\Bcris}{\mathbf{B}_{\mathrm{cris}}}
\newcommand{\Bcrisplus}{\mathbf{B}^+_{\mathrm{cris}}}

\newcommand{\bst}{\mathbf{B}_{\mathrm{st}}}
\newcommand{\Bst}{\mathbf{B}_{\mathrm{st}}}
\newcommand{\bmax}{\mathbf{B}_{\mathrm{max}}}
\newcommand{\bcont}{\mathbf{B}_{\mathrm{cont}}}

\newcommand{\bdrplus}{\mathbf{B}^+_{\mathrm{dR}}}
\newcommand{\Bdrplus}{\mathbf{B}^+_{\mathrm{dR}}}
\newcommand{\bdr}{\mathbf{B}_{\mathrm{dR}}}
\newcommand{\bdR}{\mathbf{B}_{\mathrm{dR}}}
\newcommand{\BdR}{\mathbf{B}_{\mathrm{dR}}}

\newcommand{\bHT}{\mathbf{B}_{\mathrm{HT}}}
\newcommand{\BHT}{\mathbf{B}_{\mathrm{HT}}}
\newcommand{\Asthat}{\widehat{\mathbf{A}_{\mathrm{st}}}}
\newcommand{\bigOE}{{\mathcal{O}_{\mathcal{E}}}}
\renewcommand{\OE}{{\mathcal{O}_{\mathcal{E}}}}


%%%%*************************************%%%%
%%%%*************FONTS******************%%%%
\newcommand{\llb}{\llbracket}  %for [\![u]\!].
%so \llb u \rrb, etc...
\newcommand{\rrb}{\rrbracket}
\newcommand*{\wt}[1]{\widetilde{#1}}
\newcommand*{\wh}[1]{\widehat{#1}}
\newcommand*{\mc}[1]{\mathcal{#1}}
\newcommand*{\mf}[1]{\mathfrak{#1}}
\newcommand*{\mbb}[1]{\mathbb{#1}}
\newcommand*{\mbf}[1]{\mathbf{#1}}

\newcommand{\Z}{\mathbb{Z}}
\newcommand{\Q}{\mathbb{Q}}
\newcommand{\Zp}{\mathbb{Z}_p}
\newcommand{\Qp}{\mathbb{Q}_p}
\newcommand{\Fp}{\mathbb{F}_p}
\newcommand{\Qpbar}{\overline{\mathbb{Q}}_p}
\newcommand{\Fpbar}{\overline{\mathbb{F}}_p}
\newcommand{\Zl}{\mathbb{Z}_{\ell}}
\newcommand{\Ql}{\mathbb{Q}_{\ell}}
%\newcommand{\A}{\mathbb{A}}
%% Underline
\def\ueps{\underline \varepsilon}
\def\upi{\underline \pi}
%% MATHCAL
%\def \E{\mathcal E}
%\renewcommand{\OE}{\mathcal{O}_E}
\newcommand{\bigM}{\mathcal{M}}
\newcommand{\cM}{\mathcal{M}}
\newcommand{\cm}{\mathcal{M}}
\newcommand{\bigD}{\mathcal{D}}
\newcommand{\bigO}{\mathcal{O}}
\newcommand{\bigN}{\mathcal{N}}
%% MATHFRAK
\newcommand{\huaS}{\mathfrak{S}}
\newcommand{\gS}{\mathfrak{S}}
\newcommand{\gs}{\mathfrak{S}}
\newcommand{\huaM}{\mathfrak{M}}
\newcommand{\gM}{\mathfrak{M}}
\newcommand{\gm}{\mathfrak{M}}
%% HAT
\def \hR {{\widehat{\mathcal R}} }
\def \hM {{\widehat{\mathfrak{M}}} }
\newcommand{\hatl}{\hat{\mathfrak{L}}}
\newcommand{\hatL}{\hat{\mathfrak{L}}}
\newcommand{\hatm}{\hat{\mathfrak{M}}}
\newcommand{\hatM}{\hat{\mathfrak{M}}}
\newcommand{\hatN}{\hat{\mathfrak{N}}}
\newcommand{\hatn}{\hat{\mathfrak{n}}}
\newcommand{\hattimes}{\widehat{\otimes}}
%%BAR
\newcommand{\barchi}{\overline{\chi}}
\newcommand{\barrho}{\overline{\rho}}
\newcommand{\chibar}{\overline{\chi}}
\newcommand{\rhobar}{\overline{\rho}}
%% TILDE
\newcommand{\tildeS}{\tilde{S}}
\newcommand{\tS}{\tilde{S}}
%%BOLD
\newcommand{\bolde}{\boldsymbol{e}}
\newcommand{\boldd}{\boldsymbol{d}}
%%%%*************************************%%%%


\newcommand{\A}{ {\mathbf{A}}   }
\newcommand{\B}{  {\mathbf{B}}  }
\newcommand{\wtA}{   {\widetilde{{\mathbf{A}}}}  }
\newcommand{\wtB}{   {\widetilde{{\mathbf{B}}}}  }
\newcommand{\E}{ {\mathbf{E}}}
\newcommand{\D}{ {\mathbf{D}}}
\newcommand{\vece}{\vec{e}}
\newcommand{\LHS}{\text{LHS}}
\newcommand{\RHS}{\text{RHS}}




\newcommand{\otimesvarphi}{\otimes_{\varphi}}

%***************************************************
%***************************************************
%***** Copied from Berger ***********
%***************************************************
%***************************************************
\newcommand{\ra}{\rightarrow}

\newcommand{\pibar}{\overline{\pi}}
\newcommand{\logpi}{\log[\overline{\pi}]}
\newcommand{\btst}[2]{\widetilde{\mathbf{B}}^{\dagger #1}_{\mathrm{log} #2}}
\newcommand{\btrig}[2]{\widetilde{\mathbf{B}}^{\dagger #1}_{\mathrm{rig} #2}}
\newcommand{\bnst}[2]{\mathbf{B}^{\dagger #1}_{\mathrm{log} #2}}
\newcommand{\bnrig}[2]{\mathbf{B}^{\dagger #1}_{\mathrm{rig} #2}}
\newcommand{\btstplus}[1]{\widetilde{\mathbf{B}}^{+}_{\mathrm{log} #1}}
\newcommand{\btrigplus}[1]{\widetilde{\mathbf{B}}^{+}_{\mathrm{rig} #1}}
\newcommand{\atst}[2]{\widetilde{\mathbf{A}}^{\dagger #1}_{\mathrm{log} #2}}
\newcommand{\atrig}[2]{\widetilde{\mathbf{A}}^{\dagger #1}_{\mathrm{rig} #2}}
\newcommand{\anst}[2]{\mathbf{A}^{\dagger #1}_{\mathrm{log} #2}}
\newcommand{\anrig}[2]{\mathbf{A}^{\dagger #1}_{\mathrm{rig} #2}}
\newcommand{\dnst}[1]{\mathbf{D}^{\dagger #1}_{\mathrm{log}}}
\newcommand{\dnrig}[1]{\mathbf{D}^{\dagger #1}_{\mathrm{rig}}}

 

\newcommand{\btdag}[1]{\widetilde{\mathbf{B}}^{\dagger #1}}
\newcommand{\bdag}[1]{\mathbf{B}^{\dagger #1}}
\newcommand{\bplus}{\mathbf{B}^+}
\newcommand{\btplus}{\widetilde{\mathbf{B}}^+}
\newcommand{\bt}{\widetilde{\mathbf{B}}}
\newcommand{\amax}{\mathbf{A}_{\mathrm{max}}}
\newcommand{\acont}{\mathbf{A}_{\mathrm{cont}}}
\newcommand{\atdag}[1]{\widetilde{\mathbf{A}}^{\dagger #1}}
\newcommand{\adag}[1]{\mathbf{A}^{\dagger #1}}
\newcommand{\aplus}{\mathbf{A}^+}
\newcommand{\atplus}{\widetilde{\mathbf{A}}^+}
%\newcommand{\at}{\widetilde{\mathbf{A}}}
\newcommand{\bhol}[1]{\mathbf{B}^+_{\mathrm{rig} #1}}
\newcommand{\blog}[1]{\mathbf{B}^+_{\mathrm{log} #1}}
%\newcommand{\e}{\mathbf{E}}
\newcommand{\eplus}{\mathbf{E}^+}
\newcommand{\etplus}{\widetilde{\mathbf{E}}^+}

\newcommand{\dst}{\mathbf{D}_{\mathrm{st}}}
\newcommand{\dcris}{\mathbf{D}_{\mathrm{cris}}}
\newcommand{\ddR}{\mathbf{D}_{\mathrm{dR}}}
\newcommand{\dfont}{\mathbf{D}}
\newcommand{\dfontp}{\mathbf{D'}}
\newcommand{\ddif}{\mathbf{D}_{\mathrm{dif}}}
\renewcommand{\ddag}[1]{\mathbf{D}^{\dagger #1}}
\newcommand{\dsen}{\mathbf{D}_{\mathrm{Sen}}}

\newcommand{\dbf}{\mathbf{D}}
\newcommand{\vale}{v_\mathbf{E}}
\newcommand{\ndr}{\mathbf{N}_{\mathrm{dR}}}

%*************************
%In analogy with Berger, defined by us
%**************************

\newcommand{\Mdag}[1]{\mathbf{M}^{\dagger #1}}
\newcommand{\Mnrig}[1]{\mathbf{M}^{\dagger #1}_{\mathrm{rig}}}
\newcommand{\Mnst}[1]{\mathbf{M}^{\dagger #1}_{\mathrm{log}}}


%%%%Berger Duke NOTATIONS
\newcommand{\FF}{\mathbf{F}}
\newcommand{\NN}{\mathbf{N}}
\newcommand{\ZZ}{\mathbf{Z}}
\newcommand{\OO}{\mathcal{O}}
\renewcommand{\phi}{\varphi}
\renewcommand{\div}{\mathrm{div}}
\renewcommand{\projlim}{\varprojlim}


\newcommand{\calE}{\mathcal{E}}
\newcommand{\Nm}{\mathrm{N}}
\newcommand{\calC}{\mathcal{C}}
\newcommand{\Lie}{\mathrm{Lie}}
\newcommand{\Sol}{\mathrm{Sol}}


\newcommand{\bfont}{\mathbf{B}}
\newcommand{\afont}{\mathbf{A}}
\newcommand{\efont}{\mathbf{E}}
\newcommand{\ubar}{\overline{u}}
\newcommand{\Qpnr}{\mathbf{Q}_p^{\unr}}
\newcommand{\cbf}{\mathbf{c}}
\newcommand{\ibf}{\mathbf{i}}
\newcommand{\jbf}{\mathbf{j}}
\newcommand{\kbf}{\mathbf{k}}
\newcommand{\ybf}{\mathbf{y}}
\newcommand{\unbf}{\mathbf{1}}



%%%%Berger Duke NOTATIONS



%%%%%%%Gao-Liu notations%%%%
\def \ku {k \llbracket u\rrbracket}

\def \sfi {\text{Mod}_{\mathbf{A}^+_{K_\infty}}^{\varphi, r}}
\def \sfin {\text{Mod}^{\varphi, N }_{/\mathbf{A}^+_{K_\infty}}}
\def \Sfin {{\text{Mod}_{/S}^{\varphi, N}}}
\def \Sfi {{\text{Mod}_{/S}^{\varphi}}}
\def \sfr {\text{Mod}_{/\mathbf{A}^+_{K_\infty}}^{r, \text{fr}}}
\def \ofi {\text{Mod}_{A_{K_\infty}}^{\varphi}}


 
\def \gt {\mathfrak t}
\def \CM {\mathcal M}
\def \CL {\mathcal L}
\def \CN {\mathcal N}
\def \cW {\mathcal W}
\def \cT {\mathcal T}
 
\def \Kinfty {K_{\infty}}
\def \Kpinfty {K_{p^\infty}}
%%%%%%%Gao-Liu notations%%%%


%%%%*************************************%%%%
\begin{document}
\title[]{Modules over rings}
\date{\today}
%    Information for first author
\author[]{Hui Gao}
\address{Department of Mathematics, Southern University of Science and Technology, 
Nanshan, Shenzhen, 518055 , Guangdong, China.}
\email{gaoh@sustech.edu.cn}
%    Information for second author
\author{XX}
\address{XX}
\email{XX}
%\thanks{}
%    \thanks will become a 1st page footnote.
%\thanks{The first author was}

\subjclass[2010]{Primary  11F80, 11S20}
\keywords{modules}
\begin{abstract} Let $p$ be a prime,
\end{abstract}
\maketitle
\tableofcontents
\section{Introduction}

\bibliographystyle{alpha}
\begin{thebibliography}{1}
\bibitem[XX00]{XX00}
XX
\newblock paper
 
\end{thebibliography}
\end{document}





 </font>
</html> 