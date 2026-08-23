---
layout: default
---
TVRenamer is a Java GUI utility to rename TV episodes from TV listings.
Basically, it will take an ugly filename like
**Lost.S06E05.DD51.720p.WEB-DL.AVC-FUSiON.mkv** and rename it to
**Lost [6x05] Lighthouse.mkv**

## Features

* Rename many different shows at once, using listings from [TVmaze](https://www.tvmaze.com/)
* Customise the format and content of the resulting filename
* Optionally move renamed files, to a NAS or an external drive
* Native look & feel for your operating system
* Drag & Drop or standard 'add file' interface

## [Screenshots](https://github.com/tvrenamer/tvrenamer/wiki/Screenshots)

![TVRenamer renaming ten downloaded episodes into a tidy TV library](/images/screenshot.png)

## Download

[Go to the latest release](https://github.com/tvrenamer/tvrenamer/releases/latest)
and pick the file for your operating system and processor. The macOS and Windows
downloads carry their own Java runtime, so there is nothing to install first.

| Download | For |
| --- | --- |
| `macos-aarch64.dmg` | Macs with Apple silicon (M1 and later) |
| `macos-x86_64.dmg` | Intel Macs |
| `windows-x86_64-portable.zip` | Windows on Intel or AMD |

On macOS, open the `.dmg` and drag TVRenamer to your Applications folder. The
bundles are signed and notarised, so they open without a warning.

On Windows, unzip it anywhere and run `TVRenamer\TVRenamer.exe` from inside the
folder. There is no installer, so it needs no admin rights and writes nothing to
the registry. Uninstalling means deleting the folder. Nothing on Windows is
signed yet, so SmartScreen will warn you the first time: choose 'More info',
then 'Run anyway'.

### The smaller zip

Every platform also has a plain zip of about 7MB, against 50MB for the bundles,
because it carries no Java. Linux has only this one. Install
[Java 21 or later](https://adoptium.net/) first, then take the zip matching your
system. Note that Windows has two: `windows-x86_64.zip` is this smaller one, not
the `-portable` zip above.

| Download | For |
| --- | --- |
| `linux-x86_64.zip` | Linux on Intel or AMD |
| `linux-aarch64.zip` | Linux on ARM |
| `macos-aarch64.zip` | Macs with Apple silicon (M1 and later) |
| `macos-x86_64.zip` | Intel Macs |
| `windows-x86_64.zip` | Windows on Intel or AMD |

Unzip it wherever you like and start it from the `bin` directory inside:
`bin\tvrenamer.bat` on Windows, `bin/tvrenamer` on macOS and Linux.

32-bit builds are gone. Eclipse stopped shipping 32-bit SWT natives in 2018, so
if you need one, stay on
[v1.0b4](https://github.com/tvrenamer/tvrenamer/releases/tag/v1.0b4).

## More Information

For more information see [the project page](https://github.com/tvrenamer/tvrenamer)

## Open Source, Free!!!

This project is a constant work in progress developed in our free time
[@daveharris](https://github.com/daveharris) and
[@vipuldelwadia](https://github.com/vipuldelwadia). Contributions of
[bug reports](https://github.com/tvrenamer/tvrenamer/issues) or
[pull requests](https://docs.github.com/en/pull-requests) are always gratefully
received. The source is and always will be open!
