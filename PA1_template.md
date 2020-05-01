% Options for packages loaded elsewhere
\PassOptionsToPackage{unicode}{hyperref}
\PassOptionsToPackage{hyphens}{url}
%
\documentclass[
]{article}
\usepackage{lmodern}
\usepackage{amssymb,amsmath}
\usepackage{ifxetex,ifluatex}
\ifnum 0\ifxetex 1\fi\ifluatex 1\fi=0 % if pdftex
  \usepackage[T1]{fontenc}
  \usepackage[utf8]{inputenc}
  \usepackage{textcomp} % provide euro and other symbols
\else % if luatex or xetex
  \usepackage{unicode-math}
  \defaultfontfeatures{Scale=MatchLowercase}
  \defaultfontfeatures[\rmfamily]{Ligatures=TeX,Scale=1}
\fi
% Use upquote if available, for straight quotes in verbatim environments
\IfFileExists{upquote.sty}{\usepackage{upquote}}{}
\IfFileExists{microtype.sty}{% use microtype if available
  \usepackage[]{microtype}
  \UseMicrotypeSet[protrusion]{basicmath} % disable protrusion for tt fonts
}{}
\makeatletter
\@ifundefined{KOMAClassName}{% if non-KOMA class
  \IfFileExists{parskip.sty}{%
    \usepackage{parskip}
  }{% else
    \setlength{\parindent}{0pt}
    \setlength{\parskip}{6pt plus 2pt minus 1pt}}
}{% if KOMA class
  \KOMAoptions{parskip=half}}
\makeatother
\usepackage{xcolor}
\IfFileExists{xurl.sty}{\usepackage{xurl}}{} % add URL line breaks if available
\IfFileExists{bookmark.sty}{\usepackage{bookmark}}{\usepackage{hyperref}}
\hypersetup{
  hidelinks,
  pdfcreator={LaTeX via pandoc}}
\urlstyle{same} % disable monospaced font for URLs
\usepackage[margin=1in]{geometry}
\usepackage{color}
\usepackage{fancyvrb}
\newcommand{\VerbBar}{|}
\newcommand{\VERB}{\Verb[commandchars=\\\{\}]}
\DefineVerbatimEnvironment{Highlighting}{Verbatim}{commandchars=\\\{\}}
% Add ',fontsize=\small' for more characters per line
\usepackage{framed}
\definecolor{shadecolor}{RGB}{248,248,248}
\newenvironment{Shaded}{\begin{snugshade}}{\end{snugshade}}
\newcommand{\AlertTok}[1]{\textcolor[rgb]{0.94,0.16,0.16}{#1}}
\newcommand{\AnnotationTok}[1]{\textcolor[rgb]{0.56,0.35,0.01}{\textbf{\textit{#1}}}}
\newcommand{\AttributeTok}[1]{\textcolor[rgb]{0.77,0.63,0.00}{#1}}
\newcommand{\BaseNTok}[1]{\textcolor[rgb]{0.00,0.00,0.81}{#1}}
\newcommand{\BuiltInTok}[1]{#1}
\newcommand{\CharTok}[1]{\textcolor[rgb]{0.31,0.60,0.02}{#1}}
\newcommand{\CommentTok}[1]{\textcolor[rgb]{0.56,0.35,0.01}{\textit{#1}}}
\newcommand{\CommentVarTok}[1]{\textcolor[rgb]{0.56,0.35,0.01}{\textbf{\textit{#1}}}}
\newcommand{\ConstantTok}[1]{\textcolor[rgb]{0.00,0.00,0.00}{#1}}
\newcommand{\ControlFlowTok}[1]{\textcolor[rgb]{0.13,0.29,0.53}{\textbf{#1}}}
\newcommand{\DataTypeTok}[1]{\textcolor[rgb]{0.13,0.29,0.53}{#1}}
\newcommand{\DecValTok}[1]{\textcolor[rgb]{0.00,0.00,0.81}{#1}}
\newcommand{\DocumentationTok}[1]{\textcolor[rgb]{0.56,0.35,0.01}{\textbf{\textit{#1}}}}
\newcommand{\ErrorTok}[1]{\textcolor[rgb]{0.64,0.00,0.00}{\textbf{#1}}}
\newcommand{\ExtensionTok}[1]{#1}
\newcommand{\FloatTok}[1]{\textcolor[rgb]{0.00,0.00,0.81}{#1}}
\newcommand{\FunctionTok}[1]{\textcolor[rgb]{0.00,0.00,0.00}{#1}}
\newcommand{\ImportTok}[1]{#1}
\newcommand{\InformationTok}[1]{\textcolor[rgb]{0.56,0.35,0.01}{\textbf{\textit{#1}}}}
\newcommand{\KeywordTok}[1]{\textcolor[rgb]{0.13,0.29,0.53}{\textbf{#1}}}
\newcommand{\NormalTok}[1]{#1}
\newcommand{\OperatorTok}[1]{\textcolor[rgb]{0.81,0.36,0.00}{\textbf{#1}}}
\newcommand{\OtherTok}[1]{\textcolor[rgb]{0.56,0.35,0.01}{#1}}
\newcommand{\PreprocessorTok}[1]{\textcolor[rgb]{0.56,0.35,0.01}{\textit{#1}}}
\newcommand{\RegionMarkerTok}[1]{#1}
\newcommand{\SpecialCharTok}[1]{\textcolor[rgb]{0.00,0.00,0.00}{#1}}
\newcommand{\SpecialStringTok}[1]{\textcolor[rgb]{0.31,0.60,0.02}{#1}}
\newcommand{\StringTok}[1]{\textcolor[rgb]{0.31,0.60,0.02}{#1}}
\newcommand{\VariableTok}[1]{\textcolor[rgb]{0.00,0.00,0.00}{#1}}
\newcommand{\VerbatimStringTok}[1]{\textcolor[rgb]{0.31,0.60,0.02}{#1}}
\newcommand{\WarningTok}[1]{\textcolor[rgb]{0.56,0.35,0.01}{\textbf{\textit{#1}}}}
\usepackage{graphicx,grffile}
\makeatletter
\def\maxwidth{\ifdim\Gin@nat@width>\linewidth\linewidth\else\Gin@nat@width\fi}
\def\maxheight{\ifdim\Gin@nat@height>\textheight\textheight\else\Gin@nat@height\fi}
\makeatother
% Scale images if necessary, so that they will not overflow the page
% margins by default, and it is still possible to overwrite the defaults
% using explicit options in \includegraphics[width, height, ...]{}
\setkeys{Gin}{width=\maxwidth,height=\maxheight,keepaspectratio}
% Set default figure placement to htbp
\makeatletter
\def\fps@figure{htbp}
\makeatother
\setlength{\emergencystretch}{3em} % prevent overfull lines
\providecommand{\tightlist}{%
  \setlength{\itemsep}{0pt}\setlength{\parskip}{0pt}}
\setcounter{secnumdepth}{-\maxdimen} % remove section numbering

\author{}
\date{\vspace{-2.5em}}

\begin{document}

\hypertarget{reproducible-research-peer-assessment-1}{%
\section{Reproducible Research: Peer Assessment
1}\label{reproducible-research-peer-assessment-1}}

\hypertarget{load-and-process-the-data}{%
\subsection{Load and process the data}\label{load-and-process-the-data}}

\hypertarget{load-the-data}{%
\subparagraph{1. Load the data}\label{load-the-data}}

\begin{Shaded}
\begin{Highlighting}[]
\ControlFlowTok{if}\NormalTok{(}\OperatorTok{!}\KeywordTok{file.exists}\NormalTok{(}\StringTok{'activity.csv'}\NormalTok{))\{}
    \KeywordTok{unzip}\NormalTok{(}\StringTok{'activity.zip'}\NormalTok{)}
\NormalTok{\}}
\NormalTok{activityData <-}\StringTok{ }\KeywordTok{read.csv}\NormalTok{(}\StringTok{'activity.csv'}\NormalTok{)}
\end{Highlighting}
\end{Shaded}

\hypertarget{transform-interval-data}{%
\subparagraph{2. transform interval
data}\label{transform-interval-data}}

\begin{Shaded}
\begin{Highlighting}[]
\CommentTok{#activityData$interval <- strptime(gsub("([0-9]\{1,2\})([0-9]\{2\})", "\textbackslash{}\textbackslash{}1:\textbackslash{}\textbackslash{}2", activityData$interval), format='%H:%M')}
\end{Highlighting}
\end{Shaded}

\begin{center}\rule{0.5\linewidth}{0.5pt}\end{center}

\hypertarget{mean-total-number-of-steps-taken-per-day.}{%
\subsection{mean total number of steps taken per
day.}\label{mean-total-number-of-steps-taken-per-day.}}

\begin{Shaded}
\begin{Highlighting}[]
\NormalTok{stepsByDay <-}\StringTok{ }\KeywordTok{tapply}\NormalTok{(activityData}\OperatorTok{$}\NormalTok{steps, activityData}\OperatorTok{$}\NormalTok{date, sum, }\DataTypeTok{na.rm=}\OtherTok{TRUE}\NormalTok{)}
\end{Highlighting}
\end{Shaded}

\hypertarget{histogram-of-the-total-number-of-steps-taken-each-day}{%
\subparagraph{1. Histogram of the total number of steps taken each
day}\label{histogram-of-the-total-number-of-steps-taken-each-day}}

\begin{Shaded}
\begin{Highlighting}[]
\KeywordTok{qplot}\NormalTok{(stepsByDay, }\DataTypeTok{xlab=}\StringTok{'Total steps per day'}\NormalTok{, }\DataTypeTok{ylab=}\StringTok{'Frequency using binwith 500'}\NormalTok{, }\DataTypeTok{binwidth=}\DecValTok{500}\NormalTok{)}
\end{Highlighting}
\end{Shaded}

\includegraphics{PA1_template_files/figure-latex/unnamed-chunk-5-1.pdf}

\hypertarget{mean-and-median-total-number-of-steps-taken-per-day}{%
\subparagraph{2. Mean and median total number of steps taken per
day}\label{mean-and-median-total-number-of-steps-taken-per-day}}

\begin{Shaded}
\begin{Highlighting}[]
\NormalTok{stepsByDayMean <-}\StringTok{ }\KeywordTok{mean}\NormalTok{(stepsByDay)}
\NormalTok{stepsByDayMedian <-}\StringTok{ }\KeywordTok{median}\NormalTok{(stepsByDay)}
\end{Highlighting}
\end{Shaded}

\begin{itemize}
\tightlist
\item
  Mean: 9354.2295082
\item
  Median: 10395
\end{itemize}

\begin{center}\rule{0.5\linewidth}{0.5pt}\end{center}

\hypertarget{average-daily-activity-pattern}{%
\subsection{Average daily activity
pattern?}\label{average-daily-activity-pattern}}

\begin{Shaded}
\begin{Highlighting}[]
\NormalTok{averageStepsPerTimeBlock <-}\StringTok{ }\KeywordTok{aggregate}\NormalTok{(}\DataTypeTok{x=}\KeywordTok{list}\NormalTok{(}\DataTypeTok{meanSteps=}\NormalTok{activityData}\OperatorTok{$}\NormalTok{steps), }\DataTypeTok{by=}\KeywordTok{list}\NormalTok{(}\DataTypeTok{interval=}\NormalTok{activityData}\OperatorTok{$}\NormalTok{interval), }\DataTypeTok{FUN=}\NormalTok{mean, }\DataTypeTok{na.rm=}\OtherTok{TRUE}\NormalTok{)}
\end{Highlighting}
\end{Shaded}

\hypertarget{time-series-plot}{%
\subparagraph{1. Time series plot}\label{time-series-plot}}

\begin{Shaded}
\begin{Highlighting}[]
\KeywordTok{ggplot}\NormalTok{(}\DataTypeTok{data=}\NormalTok{averageStepsPerTimeBlock, }\KeywordTok{aes}\NormalTok{(}\DataTypeTok{x=}\NormalTok{interval, }\DataTypeTok{y=}\NormalTok{meanSteps)) }\OperatorTok{+}
\StringTok{    }\KeywordTok{geom_line}\NormalTok{() }\OperatorTok{+}
\StringTok{    }\KeywordTok{xlab}\NormalTok{(}\StringTok{"5-minute interval"}\NormalTok{) }\OperatorTok{+}
\StringTok{    }\KeywordTok{ylab}\NormalTok{(}\StringTok{"average number of steps taken"}\NormalTok{) }
\end{Highlighting}
\end{Shaded}

\includegraphics{PA1_template_files/figure-latex/unnamed-chunk-8-1.pdf}
\#\#\#\#\# 2. The 5-minute interval on average across all the days in
the dataset that contains the maximum number of steps?

\begin{Shaded}
\begin{Highlighting}[]
\NormalTok{mostSteps <-}\StringTok{ }\KeywordTok{which.max}\NormalTok{(averageStepsPerTimeBlock}\OperatorTok{$}\NormalTok{meanSteps)}
\NormalTok{timeMostSteps <-}\StringTok{  }\KeywordTok{gsub}\NormalTok{(}\StringTok{"([0-9]\{1,2\})([0-9]\{2\})"}\NormalTok{, }\StringTok{"}\CharTok{\textbackslash{}\textbackslash{}}\StringTok{1:}\CharTok{\textbackslash{}\textbackslash{}}\StringTok{2"}\NormalTok{, averageStepsPerTimeBlock[mostSteps,}\StringTok{'interval'}\NormalTok{])}
\end{Highlighting}
\end{Shaded}

\begin{itemize}
\tightlist
\item
  Most Steps at: 8:35
\end{itemize}

\begin{center}\rule{0.5\linewidth}{0.5pt}\end{center}

\hypertarget{missing-values}{%
\subsection{Missing values}\label{missing-values}}

\hypertarget{the-total-number-of-missing-values-in-the-dataset}{%
\subparagraph{1. The total number of missing values in the
dataset}\label{the-total-number-of-missing-values-in-the-dataset}}

\begin{Shaded}
\begin{Highlighting}[]
\NormalTok{numMissingValues <-}\StringTok{ }\KeywordTok{length}\NormalTok{(}\KeywordTok{which}\NormalTok{(}\KeywordTok{is.na}\NormalTok{(activityData}\OperatorTok{$}\NormalTok{steps)))}
\end{Highlighting}
\end{Shaded}

\begin{itemize}
\tightlist
\item
  Number of missing values: 2304
\end{itemize}

\hypertarget{devise-a-strategy-for-filling-in-all-of-the-missing-values-in-the-dataset.}{%
\subparagraph{2. Devise a strategy for filling in all of the missing
values in the
dataset.}\label{devise-a-strategy-for-filling-in-all-of-the-missing-values-in-the-dataset.}}

\hypertarget{create-a-new-dataset-that-is-equal-to-the-original-dataset-but-with-the-missing-data-filled-in.}{%
\subparagraph{3. Create a new dataset that is equal to the original
dataset but with the missing data filled
in.}\label{create-a-new-dataset-that-is-equal-to-the-original-dataset-but-with-the-missing-data-filled-in.}}

\begin{Shaded}
\begin{Highlighting}[]
\NormalTok{activityDataImputed <-}\StringTok{ }\NormalTok{activityData}
\NormalTok{activityDataImputed}\OperatorTok{$}\NormalTok{steps <-}\StringTok{ }\KeywordTok{impute}\NormalTok{(activityData}\OperatorTok{$}\NormalTok{steps, }\DataTypeTok{fun=}\NormalTok{mean)}
\end{Highlighting}
\end{Shaded}

\hypertarget{histogram-of-the-total-number-of-steps-taken-each-day-1}{%
\subparagraph{4. Histogram of the total number of steps taken each
day}\label{histogram-of-the-total-number-of-steps-taken-each-day-1}}

\begin{Shaded}
\begin{Highlighting}[]
\NormalTok{stepsByDayImputed <-}\StringTok{ }\KeywordTok{tapply}\NormalTok{(activityDataImputed}\OperatorTok{$}\NormalTok{steps, activityDataImputed}\OperatorTok{$}\NormalTok{date, sum)}
\KeywordTok{qplot}\NormalTok{(stepsByDayImputed, }\DataTypeTok{xlab=}\StringTok{'Total steps per day (Imputed)'}\NormalTok{, }\DataTypeTok{ylab=}\StringTok{'Frequency using binwith 500'}\NormalTok{, }\DataTypeTok{binwidth=}\DecValTok{500}\NormalTok{)}
\end{Highlighting}
\end{Shaded}

\includegraphics{PA1_template_files/figure-latex/unnamed-chunk-12-1.pdf}

\hypertarget{and-calculate-and-report-the-mean-and-median-total-number-of-steps-taken-per-day.}{%
\subparagraph{\ldots{} and Calculate and report the mean and median
total number of steps taken per
day.}\label{and-calculate-and-report-the-mean-and-median-total-number-of-steps-taken-per-day.}}

\begin{Shaded}
\begin{Highlighting}[]
\NormalTok{stepsByDayMeanImputed <-}\StringTok{ }\KeywordTok{mean}\NormalTok{(stepsByDayImputed)}
\NormalTok{stepsByDayMedianImputed <-}\StringTok{ }\KeywordTok{median}\NormalTok{(stepsByDayImputed)}
\end{Highlighting}
\end{Shaded}

\begin{itemize}
\tightlist
\item
  Mean (Imputed): \ensuremath{1.0766189\times 10^{4}}
\item
  Median (Imputed): \ensuremath{1.0766189\times 10^{4}}
\end{itemize}

\begin{center}\rule{0.5\linewidth}{0.5pt}\end{center}

\hypertarget{are-there-differences-in-activity-patterns-between-weekdays-and-weekends}{%
\subsection{Are there differences in activity patterns between weekdays
and
weekends?}\label{are-there-differences-in-activity-patterns-between-weekdays-and-weekends}}

\hypertarget{create-a-new-factor-variable-in-the-dataset-with-two-levels-weekday-and-weekend-indicating-whether-a-given-date-is-a-weekday-or-weekend-day.}{%
\subparagraph{1. Create a new factor variable in the dataset with two
levels ??? ???weekday??? and ???weekend??? indicating whether a given
date is a weekday or weekend
day.}\label{create-a-new-factor-variable-in-the-dataset-with-two-levels-weekday-and-weekend-indicating-whether-a-given-date-is-a-weekday-or-weekend-day.}}

\begin{Shaded}
\begin{Highlighting}[]
\NormalTok{activityDataImputed}\OperatorTok{$}\NormalTok{dateType <-}\StringTok{  }\KeywordTok{ifelse}\NormalTok{(}\KeywordTok{as.POSIXlt}\NormalTok{(activityDataImputed}\OperatorTok{$}\NormalTok{date)}\OperatorTok{$}\NormalTok{wday }\OperatorTok{%in%}\StringTok{ }\KeywordTok{c}\NormalTok{(}\DecValTok{0}\NormalTok{,}\DecValTok{6}\NormalTok{), }\StringTok{'weekend'}\NormalTok{, }\StringTok{'weekday'}\NormalTok{)}
\end{Highlighting}
\end{Shaded}

\hypertarget{panel-plot-containing-a-time-series-plot}{%
\subparagraph{2. Panel plot containing a time series
plot}\label{panel-plot-containing-a-time-series-plot}}

\begin{Shaded}
\begin{Highlighting}[]
\NormalTok{averagedActivityDataImputed <-}\StringTok{ }\KeywordTok{aggregate}\NormalTok{(steps }\OperatorTok{~}\StringTok{ }\NormalTok{interval }\OperatorTok{+}\StringTok{ }\NormalTok{dateType, }\DataTypeTok{data=}\NormalTok{activityDataImputed, mean)}
\KeywordTok{ggplot}\NormalTok{(averagedActivityDataImputed, }\KeywordTok{aes}\NormalTok{(interval, steps)) }\OperatorTok{+}\StringTok{ }
\StringTok{    }\KeywordTok{geom_line}\NormalTok{() }\OperatorTok{+}\StringTok{ }
\StringTok{    }\KeywordTok{facet_grid}\NormalTok{(dateType }\OperatorTok{~}\StringTok{ }\NormalTok{.) }\OperatorTok{+}
\StringTok{    }\KeywordTok{xlab}\NormalTok{(}\StringTok{"5-minute interval"}\NormalTok{) }\OperatorTok{+}\StringTok{ }
\StringTok{    }\KeywordTok{ylab}\NormalTok{(}\StringTok{"avarage number of steps"}\NormalTok{)}
\end{Highlighting}
\end{Shaded}

\includegraphics{PA1_template_files/figure-latex/unnamed-chunk-15-1.pdf}

\end{document}
