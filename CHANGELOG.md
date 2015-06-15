# Change Log
All notable changes to this project are documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased](https://github.com/ravage84/SwissPaymentSlipTcpdf/compare/0.12.1...master)
### Added
- Added note about OCR-B to the requirements in the README
- Added testing with PHP 7.0 & HHVM to Travis, allow failures

### Changed
- Updated PHP dependency to 5.4 or higher
- Relaxed version of swiss-payment-slip/swiss-payment-slip-pdf dependency to 0.13.*
- Relaxed version of tecnick.com/tcpdf dependency to 6.2.*
- Added PDFs generated through the examples to the ignore list
- Changed to short array syntax

### Fixed
- Various minor fixes (change log, examples, doc blocks & CS)

## [0.12.1](https://github.com/ravage84/SwissPaymentSlipTcpdf/releases/tag/0.12.1) - 2015-02-19
### Changed
- Updated the swiss-payment-slip/swiss-payment-slip-pdf dependency to version 0.13.1 (API compatible)

## [0.12.0](https://github.com/ravage84/SwissPaymentSlipTcpdf/releases/tag/0.12.0) - 2015-02-19
### Changed
- Updated the swiss-payment-slip/swiss-payment-slip-pdf dependency to version 0.13.0 (API breaking)

## [0.11.0](https://github.com/ravage84/SwissPaymentSlipTcpdf/releases/tag/0.11.0) - 2015-02-19
### Changed
- Updated the swiss-payment-slip/swiss-payment-slip-pdf dependency to version 0.12.0 (API breaking)

## [0.10.0](https://github.com/ravage84/SwissPaymentSlipTcpdf/releases/tag/0.10.0) - 2015-02-19
### Changed
- Updated the swiss-payment-slip/swiss-payment-slip-pdf dependency to version 0.11.0 (API breaking)

## [0.9.0](https://github.com/ravage84/SwissPaymentSlipTcpdf/releases/tag/0.9.0) - 2015-02-19
### Changed
- Updated the swiss-payment-slip/swiss-payment-slip-pdf dependency to version 0.10.0 (API breaking)

## [0.8.0](https://github.com/ravage84/SwissPaymentSlipTcpdf/releases/tag/0.8.0) - 2015-02-19
### Changed
- Updated the swiss-payment-slip/swiss-payment-slip-pdf dependency to version 0.9.0 (API breaking)

## [0.7.0](https://github.com/ravage84/SwissPaymentSlipTcpdf/releases/tag/0.7.0) - 2015-02-19
### Changed
- Updated the swiss-payment-slip/swiss-payment-slip-pdf dependency to version 0.8.0 (API breaking)

## [0.6.1](https://github.com/ravage84/SwissPaymentSlipTcpdf/releases/tag/0.6.1) - 2015-02-19
### Changed
- Updated the swiss-payment-slip/swiss-payment-slip-pdf dependency to version 0.7.1 (API compatible)

## [0.6.0](https://github.com/ravage84/SwissPaymentSlipTcpdf/releases/tag/0.6.0) - 2015-02-19
### Added
- This change log
- Scrutinizer CI integration & badges
- .editorconfig file
- PHPUnit 3.7.38 as development dependency
- PHPCS 2.1.* as development dependency
- Testing with newer PHP versions and HHVM through Travis CI
- composer.lock (not ignored anymore)
- Packagist Download & Latest badges to the README
- A .gitattributes
- A bunch of incomplete tests

### Changed
- Set swiss-payment-slip/swiss-payment-slip-pdf dependency to 0.7.0
  Earlier versions can't resolve properly because they depend on dev-master of swiss-payment-slip/swiss-payment-slip
- Remove set minimum-stability ("dev"), get stable version of dependencies
- Set tecnick.com/tcpdf dependency to 6.2.6
- Fully adopted the PSR2 Code Style
- Renamed SwissPaymentSlipTcpdf to PaymentSlipTcpdf
- Adopted the PSR-4 autoloader standard
- Improved CS, DobBlocks and documentation
- Exclude development/testing only related stuff from the Composer package
- Implement a fluent interface

### Fixed
- Removed misleading time key, which fooled Packagist

## [0.5.0](https://github.com/ravage84/SwissPaymentSlipTcpdf/releases/tag/0.5.0) - 2013-07-04
### Added
- The README

### Changed
- Added DocBlocks everywhere, some other minor clean up
- Completed SwissInpaymentSlipTest
- Improved the composer.json
- Renamed namespace Gridonic\ESR to more general, library style SwissPaymentSlip\SwissPaymentSlip
- Removed SwissPaymentSlipData and SwissPaymentSlip classes and its associated files (moved them to a separate repo)
- Removed SwissPaymentSlipPdf class and and added it as dependency to composer.json
- Removed SwissPaymentSlipFPdf class and its associated files, updated composer.json. What's left is only TCPDF related
- Renamed the repo to SwissPaymentSlipTcpdf

## [0.4.0](https://github.com/ravage84/SwissPaymentSlipTcpdf/releases/tag/0.4.0) - 2013-03-05
### Changed
- Changed parameter order (height, width --> width, height) in setSlipSize and
  its protected setters in SwissInpaymentSlip

## [0.3.0](https://github.com/ravage84/SwissPaymentSlipTcpdf/releases/tag/0.3.0) - 2013-03-05
### Changed
- Changed parameter order (height, width --> width, height) in various setters in SwissInpaymentSlip

## [0.2.0](https://github.com/ravage84/SwissPaymentSlipTcpdf/releases/tag/0.2.0) - 2013-03-05
### Changed
- Major refactoring (including):
  Renamed SwissInpaymentSlip to SwissInpaymentSlipData
  Renamed SwissInpaymentSlipPdf to SwissInpaymentSlip
  Removed FPDF specific code from SwissInpaymentSlipPdf into new SwissInpaymentSlipFpdf

## [0.0.1](https://github.com/ravage84/SwissPaymentSlipTcpdf/releases/tag/0.0.1) - 2013-02-23
### Added
- Initial commit based on [peschee/class.Einzahlungsschein.php](https://github.com/peschee/class.Einzahlungsschein.php)
