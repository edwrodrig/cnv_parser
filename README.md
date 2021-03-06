edwrodrig\cnv_reader
========
A php library to read CNV files generated from CTD devices.

[![Latest Stable Version](https://poser.pugx.org/edwrodrig/cnv_reader/v/stable)](https://packagist.org/packages/edwrodrig/cnv_reader)
[![Total Downloads](https://poser.pugx.org/edwrodrig/cnv_reader/downloads)](https://packagist.org/packages/edwrodrig/cnv_reader)
[![License](https://poser.pugx.org/edwrodrig/cnv_reader/license)](https://packagist.org/packages/edwrodrig/cnv_reader)
[![Build Status](https://travis-ci.org/edwrodrig/cnv_reader.svg?branch=master)](https://travis-ci.org/edwrodrig/cnv_reader)
[![codecov.io Code Coverage](https://codecov.io/gh/edwrodrig/cnv_reader/branch/master/graph/badge.svg)](https://codecov.io/github/edwrodrig/cnv_reader?branch=master)
[![Code Climate](https://codeclimate.com/github/edwrodrig/cnv_reader/badges/gpa.svg)](https://codeclimate.com/github/edwrodrig/cnv_reader)


## My use cases

 - Read files of CTD devices exported from [SeaBird software]((http://www.seabird.com/software))
 - Compliant to [this specification](http://www.odb.ntu.edu.tw/Thermosalinograph/instrument/SBEDataProcessing.pdf)
My infrastructure is targeted to __Ubuntu 16.04__ machines with last __php7.4__ installed from [ppa:ondrej/php](https://launchpad.net/~ondrej/+archive/ubuntu/php).

## Documentation
The source code is documented using [phpDocumentor](http://docs.phpdoc.org/references/phpdoc/basic-syntax.html) style,
so it should pop up nicely if you're using IDEs like [PhpStorm](https://www.jetbrains.com/phpstorm) or similar.

### Examples
See how to read a cnv file [here](https://github.com/edwrodrig/cnv_reader/tree/master/examples/read_file.php)

## Composer
```
composer require edwrodrig/cnv_reader
```

## Testing
The test are built using PhpUnit. It generates images and compare the signature with expected ones. Maybe some test fails due metadata of some generated images, but at the moment I haven't any reported issue.

## License
MIT license. Use it as you want at your own risk.

## About language
I'm not a native english writer, so there may be a lot of grammar and orthographical errors on text, I'm just trying my best. But feel free to correct my language, any contribution is welcome and for me they are a learning instance.

