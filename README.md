# Markdown for OpenFoundry

This is a simple fork of the [Markdown](http://daringfireball.net/projects/markdown/) tool for the usage of [OpenFoundry News](http://www.openfoundry.org/en/news).

The modified parts include:

* Horizontal rule

    A horizontal rule can be along with an optional id for the tag. Such as:
    
        *** system-readmore
    will produce
    
        <hr id="system-readmore" />
* Link

    Inline link will be added a "_blank" target property. Url will be showed after link text to meet the requirement of OpenFoundry News.
    
        [Enyo 2.0](http://enyojs.com/)
    will produce
    
        <a href="http://enyojs.com/" target="_blank">Enyo 2.0</a> (http://enyojs.com/)