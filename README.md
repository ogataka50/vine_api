vine_api
========

This is a PHP library to get vine info.

This is need HTTP_Request2

```
  pear install HTTP_Request2
```


##  Example

```
	require_once dirname(__FILE__) . '/vine_api.php';
	$ret = Vine_api::get_tag_timeline('hawaii'));
```
