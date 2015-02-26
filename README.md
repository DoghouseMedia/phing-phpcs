Phing PHP_CodeSniffer
=====================

## Overview

A collection of targets for PHP_CodeSniffer.

## Installation

This project can be checked out with Composer.

```
"require": {
    "jorgegc/phing-phpcs": "*"
}
```

If you are already running a Phing build in an existing project why not
include these tasks as well with the following line in your build.xml:

```
<import file="vendor/jorgegc/phing-phpcs/build.xml" optional="true" />
```

## Usage

To get a list of tasks.

```
phing -l
```
