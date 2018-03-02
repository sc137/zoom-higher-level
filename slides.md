% Reveal Presentation Template
% Sable Cantus
% <date>

#
Fork this repo
[GIT URL](https://sc137.github.io/reveal_pres_template/)

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
![](https://cdn.pixabay.com/photo/2017/10/18/22/47/cat-2865806_1280.jpg)