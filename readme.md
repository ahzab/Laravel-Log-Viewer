# Log Viewer

A simple bundle to display your log files.

## Installation

```bsh
php artisan bundle:install logviewer
```

Then edit your application/bundles.php file and add:

```php
return array(
	'logviewer' => array(
		'location' => 'logviewer',
		'handles' => 'logviewer'
	)
);
```

