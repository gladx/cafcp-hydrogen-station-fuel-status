# CAFCP Hydrogen Station Fuel Status

[![Actions Status](https://github.com/mechawrench/cafcp-hydrogen-station-fuel-status/workflows/PHPUnit/badge.svg)](https://github.com/mechawrench/cafcp-hydrogen-station-fuel-status/actions) [![StyleCI Status](https://github.styleci.io/repos/214307467/shield)](https://github.styleci.io/repos/214307467)


Retrieves the hydrogen station fuel availability status from CAFCP.  Lists both H70 and H35 status and quantity.  This package was written for integration with Laravel 6.

## Installation

You can install the package via composer:

```bash
composer require mechawrench/cafcp-hydrogen-station-fuel-status
```

## Usage

``` php
$station = CafcpHydrogenStationFuelStatus::getStationStatus('Diamond Bar');

$statusH70 = $station['statusH70'];
```

## Find All Locations directly from CAFCP
https://cafcp.org/stationmap

### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [Mechawrench](https://github.com/mechawrench)
- [All Contributors](../../contributors)

## License
[MIT](https://github.com/mechawrench/cafcp-hydrogen-station-fuel-statuss/blob/master/LICENSE.md)
