# miBadger

Less than a framework, more than a library.

## Documentation

1. You can find examples in the README.md files of each component.
2. You can find documentation in the docs folder of each component.
3. You can generate docs with [phpDocumentor](https://www.phpdoc.org).
4. You can view the code at GitHub.

## PSR

- [PSR-1: Basic Coding Standard](http://www.php-fig.org/psr/psr-1/)
- [PSR-2: Coding Style Guide](http://www.php-fig.org/psr/psr-2/)
- [PSR-3: Logger Interface](http://www.php-fig.org/psr/psr-3/)
- [PSR-4: Autoloader](http://www.php-fig.org/psr/psr-4/)
- [PSR-6: Caching Interface](http://www.php-fig.org/psr/psr-6/)
- [PSR-7: HTTP Message Interfaces](http://www.php-fig.org/psr/psr-7/)

There is one exception on PSR 2. We use tabs instead of 4 spaces for indentation. We believe this character is meant for indentation and readers and editors should be able to change the indentation width (3 spaces, 4 spaces, etc) without changing the actual data. We also believe that it's less likely to indent incompletely since there is only one character per indentation level.

## Components

### Stable

| Component    | Version | Status                                                                                  |
| ------------ |:-------:|:---------------------------------------------------------------------------------------:|
| Enum         | 1.*     | ![Build Status](https://travis-ci.org/miBadger/miBadger.Enum.svg?branch=master)         |
| Event        | 1.*     | ![Build Status](https://travis-ci.org/miBadger/miBadger.Event.svg?branch=master)        |
| File         | 1.*     | ![Build Status](https://travis-ci.org/miBadger/miBadger.File.svg?branch=master)         |
| Http         | 1.*     | ![Build Status](https://travis-ci.org/miBadger/miBadger.Http.svg?branch=master)         |
| Log          | 1.*     | ![Build Status](https://travis-ci.org/miBadger/miBadger.Log.svg?branch=master)          |
| Mvc          | 1.*     | ![Build Status](https://travis-ci.org/miBadger/miBadger.Mvc.svg?branch=master)          |
| Observer     | 1.*     | ![Build Status](https://travis-ci.org/miBadger/miBadger.Observer.svg?branch=master)     |
| Pagination   | 1.*     | ![Build Status](https://travis-ci.org/miBadger/miBadger.Pagination.svg?branch=master)   |
| Router       | 1.*     | ![Build Status](https://travis-ci.org/miBadger/miBadger.Router.svg?branch=master)       |
| Settings     | 1.*     | ![Build Status](https://travis-ci.org/miBadger/miBadger.Settings.svg?branch=master)     |
| Singleton    | 1.*     | ![Build Status](https://travis-ci.org/miBadger/miBadger.Singleton.svg?branch=master)    |

### Beta

| Component    | Version | Status                                                                                  |
| ------------ |:-------:|:---------------------------------------------------------------------------------------:|
| ActiveRecord | 0.*     | ![Build Status](https://travis-ci.org/miBadger/miBadger.ActiveRecord.svg?branch=master) |
| Query        | 0.*     | ![Build Status](https://travis-ci.org/miBadger/miBadger.Query.svg?branch=master)        |

### Development

| Component    | Version | Status                                                                                  |
| ------------ |:-------:|:---------------------------------------------------------------------------------------:|
| Cache        | -       | ![Build Status](https://travis-ci.org/miBadger/miBadger.Cache.svg?branch=master)        |
