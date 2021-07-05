php-simple-html-dom-parser
==========================

Version 1.9.1 - PHP 8.x compatible
PHP Simple HTML DOM Parser changelog: https://sourceforge.net/projects/simplehtmldom/files/simplehtmldom/1.9.1/


Install
-------

```
composer require caophihung94/php-simple-html-dom-parser
```

Usage
-----

```php
use HungCP\PhpSimpleHtmlDom\HtmlDomParser;

...
$dom = HtmlDomParser::str_get_html( $str );
or
$dom = HtmlDomParser::file_get_html( $file_name );

$elems = $dom->find($elem_name);
...

```
