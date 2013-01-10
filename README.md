# LESS Elements TextMate bundle

This [TextMate](http://macromates.com/ "TextMate — The Missing Editor for Mac OS X") Bundle supports version 0.9 of [LESS Elements](http://lesselements.com/ "LESS Elements: a collection of useful LESS mixins").

## Install

Through [Git](http://git-scm.com/ "Git - Fast Version Control System"):

```
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone git://github.com/juanghurtado/less-elements.tmbundle.git
osascript -e 'tell app "TextMate" to reload bundles'
```

Without [Git](http://git-scm.com/ "Git - Fast Version Control System"):

```
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
wget http://github.com/juanghurtado/less-elements.tmbundle/tarball/master
tar zxf juanghurtado-less-elements.tmbundle*.tar.gz
rm juanghurtado-less-elements.tmbundle*.tar.gz
mv juanghurtado-less-elements.tmbundle* "less-elements.tmbundle"
osascript -e 'tell app "TextMate" to reload bundles'
```

## What is LESS Elements?

[LESS Elements](http://lesselements.com/ "LESS Elements: a collection of useful LESS mixins") is a set of useful mixins for the LESS CSS pre-processor to help you cut down the size of your stylesheets.

## What is LESS?

[LESS](http://lesscss.org/ "LESS &laquo; The Dynamic Stylesheet language") extends CSS with dynamic behavior such as variables, mixins, operations and functions.

## What is Textmate?

[TextMate](http://macromates.com/ "TextMate — The Missing Editor for Mac OS X") brings Apple's approach to operating systems into the world of text editors. By bridging UNIX underpinnings and GUI, TextMate cherry-picks the best of both worlds to the benefit of expert scripters and novice users alike.

## Contribute

If you think there is something wrong in this Bundle, please [yell at me at this project issues page](https://github.com/juanghurtado/less-elements.tmbundle/issues). If you want to make a modification by yourself, fork this project and send me the pull request.

## Authors

- Juan G. Hurtado ([@juanghurtado](http://github.com/juanghurtado))