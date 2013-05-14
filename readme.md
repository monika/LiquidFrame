# jquery.liquidFrame

Create a liquid iframe that continually resizes itself, as the browser resizes, to the width it's parent element (or other specified element) while maintaining it's aspect ratio.

## Usage

Select the iframe you want to be liquified and run the `.liquidFrame()` method on it:

```html
<article class="container video">

	<iframe class="fluid" src="http://player.vimeo.com/video/26387266" width="500" height="234" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>
			
</article>

<script>
    $('.fluid').liquidFrame();
</script>
````

### Options

By default, the width of the iframe is taken from the parent element, but you can specify the element by passing it as an argument:

```html
<script>
    $('.fluid').liquidFrame({liquidContainer: '.video'});
</script>
````

## Copyright & License

Copyright (c) 2013 Monika Hoex

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE