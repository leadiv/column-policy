column-policy
===========

Custom SASS mixin to help with the creation of custom grid layouts.

## Dependencies

This depends on SASS (version 3.3.7 or greater) and Compass (version 0.12.6 or greater) being installed on the system. All develop has been with 3.3.7 of SASS and 0.12.6 of Compass.

## Quick And Dirty Starting Point

1. Download the files in the dist folder to the folder where sass is compiled.
2. Include the mixin using `@import "path/to/sass/files/column-policy";`.
3. Prior to using the mixin set any global settings using `@include column-policy-options(...);`.
4. Prior to any calls to `column-policy` run `@include column-policy-base;`.
5. Where columns are needed use `@include column-policy(...);`
6. In the HTML markup ensure that the items that are in a grid have a column class. The default classname is `column`.
