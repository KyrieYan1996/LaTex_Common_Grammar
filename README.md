# LaTex Common Grammar
## 1.Add head file and package  
        1.\documentclass{article}
        2.\usepackage[utf8]{inputenc}
        3.\usepackage{amsmath}
   
## 2.Add title and author
        1.\title{title}
        2.\author{name}
        3.\date{Dec.2018}
![title](/img/title.png)

        4.\date{}
![no date](/img/no_date.png)
## 3.Add document
            1.\begin{document}
               ...
              \end{document}
## 4.Add abstract
        1.\begin{abstract}
          ...
          \end{abstract}
![Abstract](/img/abstract1.png)

        2.{\bf Abstract}
![Another form](/img/abstract2.png)
## 5.Add keywords or index terms
        1.{\bf keywords:}
        2.{\bf Index Terms-}
![Keywords/Index_Terms](/img/keywords.png)
## 6.Add section and subsection/subsubsection
        1.\section{Introduce}
        2.\section{Related Work}
        3.\section{Proposed Method}
        4.\subsection{Algorithm1}
            4.1.\subsubsection{A}
            4.2.\subsubsection{B}
        5.\subsection{Algorithm2}
![section_subsection](/img/1.png)
## 7.Add References
        1.\begin{thebibliography}{99}
          \bibitem{1}reference1
          \bibitem{2}reference2
          \end{thebibliography}
![Reference](/img/reference.png)
## 8.Add math tools
        \usepackage{amsmath}  //support package to use math tools
### 1.Add theorem 
        1.\newtheorem{deFination}{Def.} //new the deFination
        2.\section{Related Work}
        3.\begin{deFination} 
          definate A
          \end{deFination}
![newtheorem](/img/newtheorem.png)

**with the parameter [section]:**

        \newtheorem{defination}{Def.}[section]
![newtheorem_with_section](/img/newtheorem_with_section.png)
### 2.Add proof
        1.\newtheorem{proof}{proof}
        2.\begin{proof}
          prooooof1
          \end{proof}
        3.{\bf proof} prooof
![proof](/img/proof1.png)
### 3.Add equation
        1.\section{Equation}
         \begin{equation} //equation has a number
             a=b+c
         \end{equation}
         \begin{equation*}
             Z = X + Y
         \end{equation*}
![Equation](/img/equation.png)

        2.equation reference:
        \section{Equation}
        \begin{equation}\label{e1}
        a=b+c
        \end{equation}
        And it's easy to prove that t=d because of equation(\ref{e1})
![equation_reference](/img/equation_ref.png)
### 4.Fundamental Operation
        1.multiply:
        \begin{equation*}
             a = b \times b
        \end{equation*}
        2.fraction:
        \begin{equation*}
             a = b \times \frac{1}{c}
             a = b \times (\frac{1}{c}+d)
             a = b \times \left(\frac{1}{c}+d\right)
        \end{equation*}  
        3.multilines_format1：
        \section{Equation}
        \begin{gather*}
        a = b \times (\frac{1}{c}+d) \\
        a = b \times \left(\frac{1}{c}+d\right)
        \end{gather*}
        4.multilines_format2:
        \begin{equation*}
        \begin{split}
                a &= b \times (\frac{1}{c}+d) \\
                aaa &= b \times \left(\frac{1}{c}+d\right)
        \end{split}
        \end{equation*}
        % &= To align by =.
![multilines formula](/img/operation.png)

        5.multicolumns_align:
        \begin{align*}
        &a = b    
        &&c = d\\
        &e=f
        &&h=g
        \end{align*}
![align_multicols](/img/align_multicols.png)

        6.norm:
        \left \| Q \right \|_{2,0}
![norm](/img/norm.png)
            
