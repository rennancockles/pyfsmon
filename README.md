# Python FileSystem Monitor

Script for monitoring changes in the filesystem

&nbsp;

## Usage

Usage: pyfsmon path

&nbsp;

## Optional Arguments
Command|Description
-------|-----------
-h, --help | Show this help message and exit
-v, --version | Show program's version number and exit
-r, --recursive | Enable recursive watch
-c, --copy-files | Copy created files to a path specified by --output-path
-R, --reverse-match | Only watch files that NOT match the pattern
-M pattern | Only watch files that match the <pattern>
-m pattern | Only watch files that match the <pattern> case insensitive
-o output-path | Path to place the output files. Current directory by default
