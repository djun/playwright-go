# 🎭 [Playwright](https://github.com/microsoft/playwright) for <img src="https://user-images.githubusercontent.com/17984549/91302719-343a1d80-e7a7-11ea-8d6a-9448ef598420.png" height="35" />

[![PkgGoDev](https://pkg.go.dev/badge/github.com/mxschmitt/playwright-go)](https://pkg.go.dev/github.com/mxschmitt/playwright-go)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](http://opensource.org/licenses/MIT)
![Build Status](https://github.com/mxschmitt/playwright-go/workflows/Go/badge.svg)
[![Join Slack](https://img.shields.io/badge/join-slack-infomational)](https://aka.ms/playwright-slack) [![Coverage Status](https://coveralls.io/repos/github/mxschmitt/playwright-go/badge.svg?branch=master)](https://coveralls.io/github/mxschmitt/playwright-go?branch=master) <!-- GEN:chromium-version-badge -->[![Chromium version](https://img.shields.io/badge/chromium-89.0.4344.0-blue.svg?logo=google-chrome)](https://www.chromium.org/Home)<!-- GEN:stop --> <!-- GEN:firefox-version-badge -->[![Firefox version](https://img.shields.io/badge/firefox-84.0b9-blue.svg?logo=mozilla-firefox)](https://www.mozilla.org/en-US/firefox/new/)<!-- GEN:stop --> [![WebKit version](https://img.shields.io/badge/webkit-14.0-blue.svg?logo=safari)](https://webkit.org/)

[API reference](https://playwright.dev/#?path=docs/api.md) | [Example recipes](https://github.com/mxschmitt/playwright-go/tree/master/examples)

Playwright is a Go library to automate [Chromium](https://www.chromium.org/Home), [Firefox](https://www.mozilla.org/en-US/firefox/new/) and [WebKit](https://webkit.org/) with a single API. Playwright is built to enable cross-browser web automation that is **ever-green**, **capable**, **reliable** and **fast**.

|          | Linux | macOS | Windows |
|   :---   | :---: | :---: | :---:   |
| Chromium <!-- GEN:chromium-version -->89.0.4344.0<!-- GEN:stop --> | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| WebKit 14.1 | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Firefox <!-- GEN:firefox-version -->84.0b9<!-- GEN:stop --> | :white_check_mark: | :white_check_mark: | :white_check_mark: |

Headless execution is supported for all the browsers on all platforms.

## Installation

```
go get github.com/mxschmitt/playwright-go
```

## Capabilities

Playwright is built to automate the broad and growing set of web browser capabilities used by Single Page Apps and Progressive Web Apps.

* Scenarios that span multiple page, domains and iframes
* Auto-wait for elements to be ready before executing actions (like click, fill)
* Intercept network activity for stubbing and mocking network requests
* Emulate mobile devices, geolocation, permissions
* Support for web components via shadow-piercing selectors
* Native input events for mouse and keyboard
* Upload and download files

## Is Playwright for Go ready?

We are ready for your feedback, but we are still covering Playwright Go with the tests.

## Resources

* [Documentation](https://pkg.go.dev/github.com/mxschmitt/playwright-go)
* [API reference](https://github.com/microsoft/playwright/blob/master/docs/api.md)
* [Example recipes](https://github.com/mxschmitt/playwright-go/tree/master/examples)
