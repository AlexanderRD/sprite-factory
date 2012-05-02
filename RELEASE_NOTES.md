UNRELEASED - v1.4.3
-------------------
 * @halida added a new `margin` option to (optionally) separate images in generated spritesheet to avoid 'bleeding' when browser scales the sprite (e.g. when user increases text size)

February 29th 2012 - v1.4.2
---------------------------
 * added support for `:nocomments => true` to suppress comments in generated output stylesheet
 * added support for images in subfolders - fixes [github issue #11](https://github.com/jakesgordon/sprite-factory/issues/11)

August 5th 2011 - v1.4.1
------------------------
 * added support for `:style => :scss` to generate .scss file (even though content will be almost exactly same as .css style)
 * deprecated `:output` option and replaced it with 2 new explicit `:output_image` and `:output_style` options
 * updated RELEASE NOTES to include setup for use with Rails 3.1 asset pipeline

Auguest 5th 2011 - v1.4.0
-------------------------
 * (not available)

July 9th 2011 - v1.3.0
----------------------

 * source image file extensions now treated in case INsensitive manner (e.g. we detect both .PNG, .png and .Png)
 * added `:nocss => true` option to suppress generation of output css file (caller should use `run!` return value instead - it contains the generated css content as a string)

May 8th 2011 - v1.2.0
---------------------

 * added new `:layout => :packed` option to use bin-packing algorithm for generating rectangular sprite sheet
 * added pngcrush support

April 29th 2011 - v1.0.0
------------------------

 * original version
