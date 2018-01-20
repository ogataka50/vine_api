vine_api
========

[![CircleCI](https://circleci.com/gh/ogataka50/vine_api.svg?style=svg)](https://circleci.com/gh/ogataka50/vine_api)

* This is a PHP library to get vine info.

* This library depends on HTTP_Request2

```
  pear install HTTP_Request2
```


##  Example

```
	require_once dirname(__FILE__) . '/vine_api.php';
	$ret = Vine_api::get_tag_timeline('hawaii'));
```
