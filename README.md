P2IsGd v1.0.0
=============

A simple wrapper of [is.gd](http://is.gd) as a helper for Yii 2 Framework.

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist p2made/yii2-is-dg "*"
```

or add

```
"p2made/yii2-is-dg": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by:

```php
	$shortenedUrl = \p2made\helpers\is-gd\IsGdHelpers::shortenUrl($inputUrl);
```



