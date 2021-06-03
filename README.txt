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
4) In folder_name/main.tex add the following lines:
   \section{your_name / your_topic}
Use:
Structure your folder based on your comfort. 
All you need to do now is have all the content you want to present within or linked to your folder_name/main.tex  

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
||optional|| Overleaf with github:
----------------------------------------------------------------------------------
This overleaf template is linked to a git hub repository.
If you wish to use this facility, you first need to set up the repo:
1) Create a github repo in your github account using this template.
   a) go to: https://github.com/NMudunuru/TUDelftHorizontalBeamer
   b) click on Use this template
   c) enter necessary details.
2) In overleaf, create new project by importing your newly created repo from github. 
   You may have to link github account to overleaf when doing this for the first time.
3) Github repo and overleaf will be connected automatically.
4) You can then use the git repo as you would any other git repo.

Befor you go, here are some good practices if using in a collaborative manner:
1) Try to do any kind of continuous editing online, use git only to push bulk changes such as pushing a folder with images.
2) Just like you pull and push from local repo, you also have to pull and push from overleaf.
   a) click on menu button from within the overleaf project.
   b) select github from sync options in the menu.
   c) If overleaf has unchecked changes it will ask you to push to github
      and in case github repo is ahead it will ask you pull changes from github. 
3) It is ideal to push from overleaf to github just before pushing your local machine changes to github.
   This way you will know if there are any merge conflicts between the three sources.
   (In general we would expect not to have merge conflicts since everyone gets their own subdirectory to work with.)
4) Once you push to github from local machine, remember to pull these changes to overleaf. (Important)
5) As a last step, ensure that the new changes work as you expected once overleaf compiles the changes.
   (Your local machine latex may be different from overleaf so this is important)
6) If the beamer template is throwing errors during compilation by your local latex but works well in overleaf,
   it is better not to edit the latex files on your local machine. 
7) Do not make changes to the template / packages directly in the main branch. 
   Discuss with colleagues, and make the changes on a git branch. 
   Send a pull request when you're ready.

----------------------------------------------------------------------------------
* TO IMPROVE:
- Progress bar addition
----------------------------------------------------------------------------------

Credits:
# Author: Erwin Walraven (Original by Maarten Abbink)
# Bessa group Edit-1: Ozgur Taylan TURAN
# Bessa group Edit-2: Nanditha Mudunuru

(c) Ozgur Taylan TURAN 2020, March