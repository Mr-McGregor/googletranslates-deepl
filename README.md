# Google Translate + DeepL selection scripts

These are extremely simple shell scripts that open a new Google Translate or DeepL tab
in the default web browser showing the translation for the current selected text
(in any program).
This new version preserves line breaks, thus improving the quality of presentation and translation, especially for poetry. 


These scripts require *xsel*, which can be installed via *apt* :

*sudo apt update && sudo apt install xsel*


To use them, simply move scripts into */usr/local/bin/* folder :

*sudo mv googletranslate /usr/local/bin/*

*sudo mv deepl /usr/local/bin/*

To change translation language, replace "pt" with the code of the desired language after checking that it is accepted by Google Translate or DeepL :

*gedit /usr/local/bin/deepl*

*gedit /usr/local/bin/googletranslate*

You can then link the command to a keyboard shortcut of your
choice.

The idea came from 
[notitrans](http://www.webupd8.org/2016/03/translate-any-text-you-select-on-your.html).


