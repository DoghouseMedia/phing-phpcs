Phing PHPCS
===========

## Overview

A collection of PHP_CodeSniffer targets for Phing.

## Installation

This project can be checked out with Composer.

```
"require": {
    "doghouseagency/phing-phpcs": "*"
}
```

If you are already running a Phing build in an existing project why not
include these tasks as well with the following line in your build.xml:

```
<import file="vendor/doghouseagency/phing-phpcs/build.xml" optional="true" />
```

## Usage

To get a list of tasks.

```
phing -l
```
