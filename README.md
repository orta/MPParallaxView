# MPParallaxView

Apple TV Parallax effect in Swift.

<img src="http://i.imgur.com/evBWf3c.gif" alt="MPParallaxView example">

## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Parallax effect

There are 3 different ways to set up parallax:
* **.BasedOnHierarchyInParallaxView** - views in background moves less than views in foreground. You can increase the movement by changing multiplerOfIndexInHierarchyToParallaxOffset - this value will be multiplied by index of view in hierarchy. Default.
* **.BasedOnTag** - set a tag for a view. For instance, snowflakes image view has 13 tag which means noticeable movement. On the other hand, top view with cast members has 1 tag - almost no movement.
* **.Custom(Int)** - provide your custom value.

## Requirements

Swift 2.0, iOS 9

## Installation

MPParallaxView is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "MPParallaxView"
```

## Author

Michal Pyrka  
Twitter: [mikep_3](https://twitter.com/mike_p3)

## License

The MIT License (MIT)
Copyright (c) 2015 Droids On Roids LLC

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
