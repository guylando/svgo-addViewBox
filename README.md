# svgo-addViewBox
svgo plugin which replaces width, height attributes of an svg with viewBox attribute to make it responsive.

How to use:
1)install svgo (https://github.com/svg/svgo) using "[sudo] npm install -g svgo" command
2)drop the addViewBox.js file inside the plugins subfolder of the folder where svgo is installed
3)add "- addViewBox" in svgo.yml file which is placed in the folder where svgo is installed.
4)execute by adding --disable=removeViewBox --enable=addViewBox when executing svgo, for example: "svgo --disable=removeViewBox --enable=addViewBox file.svg"
