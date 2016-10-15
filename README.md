persain date/time extension for Yii2
====================================
persain date for yii2, source from: http://babakhani.github.io

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist shozdeh/yii2-persiandate "*"
```

or add

```
"shozdeh/yii2-persiandate": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \shozdeh\persiandate\Persaindate::widget(); ?>```