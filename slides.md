% Reveal Presentation Template
% Sable Cantus
% <date>

#
Fork this repo
[GIT URL](https://github.com/sc137/reveal_pres_template.git)

#
Update the slides.md file

#
* add bullets
* titles
* images

#
Compile to a self-contained file

    ./build.sh
    
#
    pandoc -t revealjs \
    --variable theme="black" \
    -s slides.md \
    -o index.html

#
Enable git pages FTW

#
![](img/cat.jpg)