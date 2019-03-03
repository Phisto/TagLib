[![Carthage Compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![License](https://img.shields.io/github/license/phisto/TagLib.svg)](https://github.com/Phisto/TagLib)

## Overview

This is a mirror of the [TagLib](https://taglib.org/) 1.11.1 source and will build a dynamic framework for macOS.

It is slightly tuned to address some XCode warnings and uses the project settings recommended by XCode.


## Requirements

- macOS 10.10+
- Xcode 10.1+


## Installation

### Carthage

[Carthage](https://github.com/Carthage/Carthage) is a decentralized dependency manager that builds your dependencies and provides you with binary frameworks. To integrate LAME into your Xcode project using Carthage, specify it in your `Cartfile`:

```ogdl
github "Phisto/TagLib" ~> 1.0
```


### Manually

If you prefer not to use Carthage, you can integrate TagLib into your project manually.
You only need to build and add the TagLib framework (TagLib.framework) to your project. 


## Usage

See the online  [API documentation ](https://taglib.org/api/) of the TagLib project.


## License

TagLib is released under the [GNU Lesser General Public License (LGPL)](https://www.gnu.org/licenses/). 

