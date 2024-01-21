# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

- Changed:
  - Renamed repository to `MtyLaTeXCmds`. 'Mty' is the abbreviation of 'Motchy'.

## [0.13.0] - 2024-01-18

- Changed:
  - Replaced `newcommand` with `newcommand*` (see [What's the difference between \newcommand and \newcommand*?](https://tex.stackexchange.com/questions/1050/whats-the-difference-between-newcommand-and-newcommand))
- Improved:
  - Now `escapeUnderscore` command prevents overfull hbox at the table cell.
- Added:
  - `transpose`, `HerConj` commands
  - `rsvDef`, `laterDef`, `laterEdef` commands
    - The LAST definition of the command is applied across ALL pages.

## [0.12.0] - 2023-07-07

- Deleted:
  - `expo` command
- Added:
  - `PrincipalValue`, `\rect`, `\nsinc`, `escapeUnderscore` command

## [0.11.1] - 2023-04-26

- Fixed:
  - warning about `listingsutf8` package

## [0.11.0] - 2023-04-11

- Changed:
  - Replaced `[]` with `()` in `LPLC` and `ILPLC` commands.
  - Renamed `\setParens` command with `setComprehension` command.
- Improved:
  - Avoided input encoding warning about `\inlineCode` command when compiling with LuaLaTeX.
- Added:
  - `braces` and `bracks` commands.
  - `ZTrans` and `IZTrans` commands

## [0.10.0] -2023-03-25

- Improved:
  - Renamed `\set` to `\setParens` in order to avoid conflict with `braket` package's `\set` command.

## [0.9.0] - 2022-09-27

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
