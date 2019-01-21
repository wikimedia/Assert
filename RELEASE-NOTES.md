# Assert release notes

## Version 0.4.0 (dev)
* Raised required PHP version from 5.3 to 7.0/HHVM

## Version 0.3.0 (2016-11-09)
* Added `Assert::parameterKeyType` and `ParameterKeyTypeException`
* Added `Assert::nonEmptyString`
* Added `Traversable` as a pseudo type that not only accept traversable objects but also arrays

## Version 0.2.2 (2015-04-29)
* Fixed a parameter type check in `ParameterAssertionException`

## Version 0.2.1 (2015-04-28)
* Fixed an import in `AssertTest`

## Version 0.2.0 (2015-04-13)
* Added `callable` as a pseudo type that not only accepts closures but everything `is_callable`
  accepts
* Added `AssertionException` interface
* All exception classes now implement `AssertionException`

## Version 0.1.0 (2014-07-30)

Initial release
