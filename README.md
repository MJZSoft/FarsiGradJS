#FarsiGradJS




FarsiGradJS is a JavaScript library for making Persian (Farsi) or Arabic gradient colored text in web pages or any other technologies that supports HTML syntax. 

You can see a sample output of this library in the last line of the following picture:


![Image of Persian Golf](https://raw.githubusercontent.com/mjza/FarsiGradJS/master/SampleOutput.PNG)


Making gradient text sometimes is hectic. While it is supported in some new browsers via CSS there are some other older browsers that cannot create gradient text correctly (At the moment of writing this kind of gradient text just supported in Google Chrome and Edge browsers).

Thus there are some online services like http://patorjk.com/text-color-fader/ that receive a sample text and create a series of SPAN tags with different text colors.

This kind of services works fine for latin text that their characters are separated naturally. 

If someone tries to make a Persian or Arabic text gradient with this kind of services he will receive a separated sentance as this kind of services do not support languages like Persian that have connected letters. 

This library can solve this problem by generating suitable gradient texts.

If you want to see a Demo of this library you can download the whole project and simply run the index.html file or you can visit the following address: https://jsfiddle.net/mjza/c6gsna2j/

You can easily find the minified file in the CDN via following links:

http://cdn.jsdelivr.net/farsigradjs/1.0.5/farsigrad-min.js

http://cdn.jsdelivr.net/farsigradjs/1.0.5/farsigrad.js
