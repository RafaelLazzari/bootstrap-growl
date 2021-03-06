I just wanted to give everyone an update due to the amount of views/pull request this has gotten, I thought I would post this update. I recently had a death within my family, this put me behind in both my work and business. I may not be able to review many updates or issues until the end of the month. Thank you for your understanding.

# Bootstrap Growl
This is a simple pluging that turns standard Bootstrap alerts into "Growl-like" notifications.


## Bower Officially Supported
I would like to thank [Błażej Krysiak](https://github.com/IjinPL) for doing this!
```
bower install bootstrap.growl 
```

## Changelog
##### Version 2.0.1
- Added the ability to set an X and Y value within the offset option
- Added callback options onShow, onShown, onHide and onHidden
- Added a close all method to close all open growls

##### [Version 2.0.0a3](http://bootstrap-growl.remabledesigns.com/2.0.0a3/)
- Fixed issue with growl not closing if there was no CSS animations

##### [Version 2.0.0a2](http://bootstrap-growl.remabledesigns.com/2.0.0a2/) (with IE8 Support)
- Changed animate.in to animate.enter for IE8 compatibility
- Changed animate.out to animate.exit for IE8 compatibility
- Modified .is(':hover') for IE8 compatibility

##### [Version 2.0.0a1](http://bootstrap-growl.remabledesigns.com/2.0.0a1/)
- Better Minification

##### [Version 2.0.0a](http://bootstrap-growl.remabledesigns.com/2.0.0a1/)
- Major rewright of the plugin file.
- Added the ability to pass the growl a link making it clickable.
- Added the ability to control the growl animations in and out using css.
- Added the ability to set growl settings globally.
- Removed jQuery fadeIn (use css to control growl animations)

##### [Version 1.0.6](http://bootstrap-growl.remabledesigns.com/1.0.6/)
- Added onGrowlShow and onGrowlShown callback functionality.

##### Version 1.0.5
- Better positioning when using CSS animations after growl closes.

##### Version 1.0.4
- Updated $.growl() to return a wrapper object with a small API to let you control individual notifications after they have been created.
- Added onGrowlClose and onGrowlClosed callback functionality.

##### Version 1.0.3
- Made jQuery $.extend() Recursive so when you change just one option under position or template the script wont fail

##### Version 1.0.2
- Fixed an issue where $.growl("message") would thrown an exception | Provided by [DannyJo](https://github.com/DannyJo/bootstrap-growl)

##### Version 1.0.0
- Initial Release

## Demo
I have created a small demo to show off some of the features that you can use with this plugin. http://bootstrap-growl.remabledesigns.com/

## Dependencies
- [jQuery v1.10.2](http://jquery.com/)
- [Bootstrap v2.0.0 - 3.2.0](http://getbootstrap.com/)


## Documentation
There is alot of documentation on the website. Click the link below to read it.
- [Documentation](http://bootstrap-growl.remabledesigns.com/#growl-documentation)

## Copyright and License
The MIT License (MIT)
Copyright (c) 2014 Robert McIntosh

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
