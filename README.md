# php-holidayapi
Official PHP library for [CalendarIndex API](https://www.calendarindex.com)

## Installation

```shell
composer require "calendarindex/php-calendarindex:dev-master"
```

## Usage

```php
$ciapi = new CalendarIndex\v1('_YOUR_API_KEY_');

$parameters = array(
  // Required
  'country' => 'US',
  'year'    => 2019,
  // Optional
  // 'state'  => 'CA',
  // 'region' => 'LA'
);

$response = $ciapi->holidays($parameters);
```

