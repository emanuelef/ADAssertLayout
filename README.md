# ADAssertLayout

[![Version](https://img.shields.io/cocoapods/v/AssertLayout.svg?style=flat)](https://cocoapods.org/pods/AssertLayout)
[![License](https://img.shields.io/cocoapods/l/AssertLayout.svg?style=flat)](https://cocoapods.org/pods/AssertLayout)
[![Platform](https://img.shields.io/cocoapods/p/AssertLayout.svg?style=flat)](https://cocoapods.org/pods/AssertLayout)

ADAssertLayout is a set of helpers to make layout assertions on `UIView`. The project is a Swift port of LinkedIn library [LayoutTest-iOS](https://github.com/linkedin/LayoutTest-iOS).

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Communication](#communication)
- [Credits](#credits)
- [License](#license)

## Features

- [x] Assert a view is within the bounds of its superview
- [x] Assert two siblings views are not overlaping
- [x] Assert a view has no ambiguous layout
- [x] Assert a view is before / after / above / below another view
- [x] Assert a view is aligned with another view

## Requirements

- iOS 9.0+
- Swift 4.2

## Communication

- If you **need help**, use [Twitter](https://twitter.com/applidium).
- If you'd like to **ask a general question**, use [Twitter](https://twitter.com/applidium).
- If you'd like to **apply for a job**, [email us](jobs@applidium.com).
- If you **found a bug**, open an issue.
- If you **have a feature request**, open an issue.
- If you **want to contribute**, submit a pull request.

## Installation

### CocoaPods

[CocoaPods](https://cocoapods.org) is a dependency manager for Cocoa projects. You can install it with the following command:

```bash
$ gem install cocoapods
```

To integrate ADAssertLayout into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '12.0'
use_frameworks!

target '<Your Target Name>' do
    pod 'ADAssertLayout'
end
```

Then, run the following command:

```bash
$ pod install
```

## Credits

ADAssertLayout is owned and maintained by [Fabernovel Technologies](https://technologies.fabernovel.com/). You can follow us on Twitter at [@applidium](https://twitter.com/applidium).


## License

ADAssertLayout is released under the MIT license. [See LICENSE](LICENSE) for details.
