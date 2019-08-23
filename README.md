# PINOperation

[![Build status](https://badge.buildkite.com/665147e3b6852a9c1c3a3df3ced779c32bc6396ba69fee4b6e.svg?branch=master&style=flat)](https://buildkite.com/pinterest/pinoperation)
[![CocoaPods](https://img.shields.io/cocoapods/v/PINOperation.svg)](http://cocoadocs.org/docsets/PINOperation/)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![Swift Package Manager](https://img.shields.io/badge/Swift%20Package%20Manager%20-compatible-brightgreen)](https://swift.org/package-manager/)]
[![Supported platforms](https://img.shields.io/cocoapods/p/PINOperation)]()]

## Fast, concurrency-limited task queue for iOS and macOS.

## Installation

### Manually

[Download the latest tag](https://github.com/pinterest/PINOperation/tags) and drag the `PINOperation` folder into your Xcode project.

Install the docs by double clicking the `.docset` file under `docs/`, or view them online at [cocoadocs.org](http://cocoadocs.org/docsets/PINOperation/)

### Git Submodule

    git submodule add https://github.com/pinterest/PINOperation.git
    git submodule update --init

### CocoaPods

Add [PINOperation](http://cocoapods.org/?q=name%3APINOperation) to your `Podfile` and run `pod install`.

### Carthage

Add the following line to your `Cartfile` and run `carthage update --platform ios`. Then follow [this instruction of Carthage](https://github.com/carthage/carthage#adding-frameworks-to-unit-tests-or-a-framework) to embed the framework.

```github "pinterest/PINOperation"```

### Swift Package Manager

```.package(url: "https://github.com/pinterest/PINOperation", .upToNextMajor(from: "1.1.3"))```

## Requirements

Since 1.1.3 __PINOperation__ requires iOS 8.0/watchOS 2.0/tvOS 9.0 or OS X 10.10 and greater. If you need to target lower versions please use PINOperation 1.1.2.

## Contact

[Garrett Moon](mailto:garrett@pinterest.com)

## License

Copyright 2013 Tumblr, Inc.
Copyright 2015 Pinterest, Inc.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. [See the License](LICENSE.txt) for the specific language governing permissions and limitations under the License.
