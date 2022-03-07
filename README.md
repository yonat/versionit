**VersionIt** is a script to change the version in several places:

* Xcode project version and build number
* Settings.bundle first DefaultValue
* podspec version
* git tag
* CHANGELOG.md [Unreleased] heading
* README.md occurrences of old version number

## Installation

With `curl`:

    $ curl --create-dirs -O --output-dir /usr/local/bin https://raw.githubusercontent.com/yonat/versionit/HEAD/versionit && chmod a+x /usr/local/bin/versionit

Alternatively, clone the repo and then:

    $ chmod 755 versionit
    $ mv versionit /usr/local/bin

## Usage

See help:

    $ versionit -h
