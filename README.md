#Imagine
[![Build Status](https://travis-ci.org/petervanderdoes/imagine.svg?branch=develop)](https://travis-ci.org/petervanderdoes/imagine)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/petervanderdoes/imagine/badges/quality-score.png?b=develop)](https://scrutinizer-ci.com/g/petervanderdoes/imagine/?branch=develop)

Image manipulation library for PHP 5.6+ inspired by Python's PIL and other image
libraries.

## Requirements

The Imagine library has the following requirements:

 - PHP 5.6+

Depending on the chosen Image implementation, you may need one of the following:

 - GD2
 - Imagick
 - Gmagick

### Installation using composer
Add the following to composer.json
```json
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/petervanderdoes/imagine"
    }
  ],
  "require": {
    "imagine/imagine": "dev-master"
  }
```
## Basic Principles

The main purpose of Imagine is to provide all the necessary functionality to bring all native low level image processing libraries in PHP to the same simple and intuitive OO API.

Several things are necessary to accomplish that:

* Image manipulation tools, such as resize, crop, etc.
* Drawing API - to create basic shapes and advanced charts, write text on the image
* Masking functionality - ability to apply black&white or grayscale images as masks, leading to semi-transparency or absolute transparency of the image the mask is being applied to

The above tools should be the basic foundation for a more powerful set of tools that are called ``Filters`` in Imagine.

Some of the ideas for upcoming filters:

* Charting and graphing filters - pie and bar charts, linear graphs with annotations
* Reflection - apple style
* Rounded corners - web 2.0

## Documentation

 - [Hosted by Read The Docs](http://imagine.readthedocs.org/)

## Presentations

 - [Introduction to Imagine](http://www.slideshare.net/avalanche123/introduction-toimagine)
 - [How to Take Over the World with Lithium](http://speakerdeck.com/u/nateabele/p/how-to-take-over-the-world-with-lithium?slide=33)

## Articles ##

 - [Image Processing with Imagine](http://www.phparch.com/2011/03/image-processing-with-imagine)
