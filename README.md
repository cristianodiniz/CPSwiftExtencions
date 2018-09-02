# CPSwiftExtencions

[![CI Status](https://img.shields.io/travis/cristianodiniz/CPSwiftExtencions.svg?style=flat)](https://travis-ci.org/cristianodiniz/CPSwiftExtencions)
[![Version](https://img.shields.io/cocoapods/v/CPSwiftExtencions.svg?style=flat)](https://cocoapods.org/pods/CPSwiftExtencions)
[![License](https://img.shields.io/cocoapods/l/CPSwiftExtencions.svg?style=flat)](https://cocoapods.org/pods/CPSwiftExtencions)
[![Platform](https://img.shields.io/cocoapods/p/CPSwiftExtencions.svg?style=flat)](https://cocoapods.org/pods/CPSwiftExtencions)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

CPSwiftExtencions is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'CPSwiftExtencions'
```

## How to use

----
Example of implementation
```swift
import CPSwiftExtencions

func exemple(){
    var d = Date()
    
    //add days on current date
    d.add(days: 5)
    print(d)
    
    
    //add hours on current date
    d.add(hours: 12)
    print(d)
    
    
    //add hours on current date
    d.add(minutes: 10)
    print(d)
}
```

## Author

Cristiano Diniz Pinto, cristianodp@gmail.com

## License

CPSwiftExtencions is available under the MIT license. See the LICENSE file for more info.
