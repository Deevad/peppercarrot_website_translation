# Pepper&Carrot translation project
## full website static pages
[http://www.peppercarrot.com](http://www.peppercarrot.com)

![alt tag](http://www.peppercarrot.com/data/images/lab/2015-03-02_tuto-translation/2015-03-01_g_about-website.jpg)


License
=======

[GNU GPL V3](http://www.gnu.org/copyleft/gpl.html)

## Translators and correctors:
* Chinese: Ran Zhuang

* Czech: Kateřina Fleknová

* English: David Revoy

* French: David Revoy

* Polish: Sölve Svartskogen

* Português: Frederico Batista

* Русский: Denis "uncle Night" Prisukhin


How-to:
========

To translate the website pages, just duplicate the en.php file and rename it to your country code (according the [table here](http://www.w3schools.com/tags/ref_language_codes.asp)). Then edit it with a text-editor.

1. For a typical line like this one:

``` 'FOLLOW'        =>  'Follow Pepper&amp;Carrot on :', ```

2. The first part ``` 'FOLLOW' ```  is the unique ID, do not translate it.

3. The arrow ``` => ``` links the previous field with the next one (note, you can add any amount of spacebar characters between the fields (eg. if you want to align all ``` => ``` in your file)).

4. Last field is ```'Follow Pepper&amp;Carrot on :'``` use HTML encapsuled inside ```'``` symbols. It's the content to translate. If you need a special character like the one ```&```, use the charset ```&amp;```, and if you need to use ```'```, you'll need to escape it with a backslash ```\'``` . Except that, the website is encoded in UTF8, so pretty tolerant to all euro-latino-accents, and other unicode compatible languages.

5. Last character in the line is ```,``` and mean the line is over.


## C.M.S:

* PluXml
[link](http://www.pluxml.org/)
