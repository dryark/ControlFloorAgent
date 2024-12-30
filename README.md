# ControlFloorAgent

This repo is deprecated. See [the related issue](https://github.com/dryark/ControlFloorAgent/issues/168)

ControlFloorAgent is a fork of WebDriverAgent ( WDA ).

It is a long running test for iOS that can be used to remote control iOS devices. It allows you to launch & kill applications, tap & scroll views or confirm view presence on a screen. It is a tool for app end-to-end testing or general purpose device automation. It works by linking `XCTest.framework` and calling Apple's Xctest API to execute commands directly on a device. It is developed for end-to-end testing.

## Features ( inherited from WDA )
 * Both iOS and tvOS platforms are supported with devices & simulators
 * Implements most of [WebDriver Spec](https://w3c.github.io/webdriver/webdriver-spec.html)
 * Implements part of [Mobile JSON Wire Protocol Spec](https://github.com/SeleniumHQ/mobile-spec/blob/master/spec-draft.md)

## License

[`WebDriverAgent` is BSD-licensed](LICENSE).

Many files within this fork are [Free Use Anti-Corruption License](AC_LICENSE.TXT).

It's debatable whether this project can be legally used at all considering the license mixing. You probably shouldn't.
License incompatibility does not mean you are free to use the AC licensed content under BSD terms. It just means the code hasn't been licensed at all and can't be used. This is part of why this project was abandoned and entirely rewritten.

Facebook, the original authors, provided a [patent grant](PATENTS).
