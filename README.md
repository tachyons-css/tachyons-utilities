# TACHYONS-UTILITIES

http://tachyons.io

Work In Progress. Pull requests and open issues welcome.

## Install
```
npm install --save-dev tachyons-utilities
```
or download the css on github and include in your project.

## The Code
```

/*

   UTILITIES

*/

/*
 *  The Media Object
 *  Built by @stubornella
 *  http://www.stubbornella.org/content/2010/06/25/the-media-object-saves-hundreds-of-lines-of-code/
 *
 *  <div class="media attribution">
 *
 *    <a href="http://twitter.com/stubbornella" class="img">
 *      <img src="http://stubbornella.com/profile_image.jpg" alt="me" />
 *    </a>
 *
 *    <div class="bd">
 *      @Stubbornella 14 minutes ago
 *    </div>
 *
 *   </div>
 */



/*
 * The Flag Object
 * Built by @csswizzrdry
 * http://csswizardry.com/2013/05/the-flag-object/
 *
 *
 * Use to vertically center text against an image.
 *
 *  <div class="flag">
 *      <div class="flag--image">
 *          <img src="" alt="">
 *      </div>
 *      <div class="flag--body">
 *          <p></p>
 *      </div>
 *  </div>
 *
 */

.flag {
  display: table;
  width: 100%;
}

.flag--image,
.flag--body {
    display: table-cell;
    vertical-align: middle;

    .flag--top & {
        vertical-align: top;
    }

    .flag--bottom & {
        vertical-align: bottom;
    }

}

.flag--image {
    padding-right: 10px;

    > img {
        display: block;
        max-width: none;
    }

    .flag--rev & {
        padding-right: 0;
        padding-left: 10px;
    }

}

.flag--body {
    width: 100%;
}

/*
  Aspect ratios for media objects i.e canvas, iframe, video, svg etc.
  Defaults to 16x9
*/

.aspect-ratio {
  height: 0;
  padding-top: 56.25%;
  position: relative;
}

.aspect-ratio--object {
    bottom: 0;
    height: 100%;
    left: 0;
    position: absolute;
    right: 0;
    top: 0;
    width: 100%;
    z-index: 100;
}

.overflow-container {
  overflow-y: scroll;
```}

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

