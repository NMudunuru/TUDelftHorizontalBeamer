TU Delft beamer template: Horizontal

This template can be utilized for slides in group meetings. 
Also for personal use if you like the structure ofcourse.

----------------------------------------------------------------------------------
Instructions of use in collaborative environment:
----------------------------------------------------------------------------------
Setting up:
1) Create a folder with a name of choice for example folder_name. 
   This way you can have all your content in one place.
   * No spaces in any file or folder names. 
     Overleaf / Latex does not accept that.
2) Add a ref.bib and main.tex files in your folder.
3) In presentation.tex add the following lines in corresponding sections
   a) \addbibresource{folder_name/ref.bib}
   b) \input{folder_name/main} 
Use:
Structure your folder based on your comfort. All you need to do now is have all the content you want to present within or linked to your main.tex  

----------------------------------------------------------------------------------
Latex with beamer:
----------------------------------------------------------------------------------
1) Each page is defined as a frame 
   \begin{frame}{Frame Title} contents \end{frame}

2) Pages can then be partitioned using minipage 
   \begin{minipage}{width} contents \end{minipage}
   More on positioning and sizing mini pages: http://latexref.xyz/minipage.html

3) Sections and subsections in this template appear on the navigation bars at the top.
   So use wisely ;)
   (The navigation bars on top are clickable links to corresponding pages.)

4) Tikz package is imported in this template. 
   I find it quite handy to point at things or draw attention to certain aspects in a figure.
   Links to get you started with tikz: 
   https://en.wikibooks.org/wiki/LaTeX/PGF/TikZ 
   https://www.overleaf.com/learn/latex/TikZ_package 
   https://www.bu.edu/math/files/2013/08/tikzpgfmanual.pdf

Beamer for begineers - 
https://www.overleaf.com/learn/latex/Beamer_Presentations:_A_Tutorial_for_Beginners_(Part_1)%E2%80%94Getting_Started

Documentation if you wish to become a master :P -
http://tug.ctan.org/macros/latex/contrib/beamer/doc/beameruserguide.pdf
----------------------------------------------------------------------------------

* TO IMPROVE:
- Progress bar addition

Credits:
# Author: Erwin Walraven (Original by Maarten Abbink)
# Bessa group Edit-1: Ozgur Taylan TURAN
# Bessa group Edit-2: Nanditha Mudunuru

(c) Ozgur Taylan TURAN 2020, March