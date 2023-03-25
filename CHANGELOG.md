# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.10.0]

- Improved:
  - Renamed `\set` to `\setParens` in order to avoid conflict with `braket` package's `\set` command.

## [0.9.0]

- Added:
  - new command `\inlineCode`
  - new command `\NapierE`

## [0.8.1] - 2022-08-23

- Fixed:
  - Some commands using `\renewcommand` cause error when no homonymous command is defined.

## [0.8.0] - 2022-08-22

- Changed:
  - Renamed `\cPrParen` to `\cPrParens`
- Added:
  - new command `\parens`

## [0.7.0] - 2022-06-23

- Added `cycConv` command.

## [0.6.0] - 2022-05-16

- Deleted `\integ` command.
- Added `erf` and `DFT` command.

## [0.5.0] - 2021-11-11

- Improved `\set` command appearance using `mathtools`'s `DeclarePairedDelimiterX`.
- Improved `\Pr` command appearance; replace braces with parenthesis.
- Improved `\cPr` command delimiter size control using `mathtools`'s `DeclarePairedDelimiterX`.
- Added commands for Hadamard product and division
- Added `\integrate` command, and **deprecated** `\integ` command.

## [0.4.1] - 2021-10-20

- Fixed `\range` command. Replaced `\cdots` with `\dotsc`.
- Changed linefeed code from CR+LF to LF

## [0.4.0] - 2021-06-30

- Added `partDerivIIHeteroLong` command.
- Added `argmin` command.

## [0.3.0] - 2020-12-19

- Added parenthesis for `tr` function.

## [0.2.0] - 2020/11/28

- Improved the style of `sgn` function by using `mathoperator` rather than using `mathrm`.
- Added \conj command.

## [0.1.0] - 2020/10/3

- Added sgn function

## [0.0.0] - 2020-08-3

### Added

- first release
