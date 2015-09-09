Yii2 rrssb - A social share bar for Yii2.
=========================================
This is a responsive social bar widget for Yii2 projects. 

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist imanilchaudhari/yii2-rrssb "*"
```

or add

```
"imanilchaudhari/yii2-rrssb": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \imanilchaudhari\rrssb\ShareBar::widget(['Email', 'Facebook', 'Twitter', 'GooglePlus', 'LinkedIn']); ?>```


About
-------

[Yii2-rrssb](https://github.com/kni-labs/rrssb) is inspired by [RRSSB](https://github.com/kni-labs/rrssb).
