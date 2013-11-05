lazy-tests
==========

to check if your small fix did not break anything else run at it will compare 
staging/test env screenshots with production.

a) firefox plugin to create projects json file with urls and regions to tests
b) script which takes screenshots through selenium webdriver
c) lib which diffs two screenshots (distance between pixels with some allowed small errors).

treashold can be specified of ration between pixels which diff and all pixels to raise fail assert

build on some sort of unittest library
