![Diashow](bin/images/Readme.jpg)


Diashow
========

Diashow/Slideshow Component

Package name:

    quiqqer/diashow


Features
--------

- Diashow via image list


Installation
------------

The package name is: quiqqer/diashow


Contribute
----------

- Project: https://dev.quiqqer.com/quiqqer/package-diashow
- Issue Tracker: https://dev.quiqqer.com/quiqqer/package-diashow/issues
- Source Code: https://dev.quiqqer.com/quiqqer/package-diashow/tree/master


Support
-------

If you found any flaws, have any wishes or suggestions you can send an email
to [support@pcsg.de](mailto:support@pcsg.de) to inform us about your concerns. 
We will try to respond to your request and forward it to the responsible developer.



License
-------

GPL-3.0+



Usage
-----

The package provides a diashow-control.

JavaScript:

```javascript
require(['package/quiqqer/diashow/bin/Diashow'], function(DiashowControl) {
    var Diashow = new DiashowControl({
        images      : [
            {
                src: 'https://image.path/img.png', 
                title: 'Image Title', 
                short: 'Image Description'
            }, {
                src: 'https://image.path/img2.png', 
                title: 'Image Title 2', 
                short: 'Image Description 2'
            }
        ],
        zIndex      : 1000,
        shortenShort: true
    });
    Diashow.inject(Container);
    Diashow.open();
});
```
