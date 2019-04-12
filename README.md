# TDX (TeamDynamix) Improved

[![Known Vulnerabilities](https://snyk.io/test/github/mikesprague/tdx-improved/badge.svg?targetFile=package.json)](https://snyk.io/test/github/mikesprague/tdx-improved?targetFile=package.json)
[![Greenkeeper badge](https://badges.greenkeeper.io/mikesprague/tdx-improved.svg)](https://greenkeeper.io/)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fmikesprague%2Ftdx-improved.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fmikesprague%2Ftdx-improved?ref=badge_shield)

## :construction: Work in Progress

![TDX Improved Colors](tdx-improved.png)

We use [TeamDynamix](https://www.teamdynamix.com) for issue tracking where I'm currently contracting.
I'm not the biggest fan of the software but have to spend a fair amount of time in it daily so I'll be
addressing some of the pain points I've hit while using it here.

This repo will start with some userstyles to improve the appearance of TDX from it's incredibly bright,
all white, in your face, mostly default-Bootstrap styles to something I find more bearable.

**Please Note:** On the off chance anyone finds this repo, and has a use for it, please understand
this is very much a work in progress and I'm focusing on the "screens" I spend the most time looking
at first.

### :memo: General Notes

All styles are in :file-folder:`src/scss/` and any edits should be done there. You can run
`npm run scss` from the project root and it will watch for your changes and automatically compile
the stylesheets in :file-folder:`build/css/`.

TODO: Automate the building of the `build/userstyles-mozilla.css` file. Currently, the file is
being built manually - I copy the generated styles into the corresponding sections of that file.

### :sparkles: Installation

Currently, you must use a 3rd party browser extension that supports userstles. I, personally, use
Stylus these days but formerly used Stylish. Both are available for most browsers. NOTE: Stylus has
an option to automatically check for updates to installed userstyles - I'm not sure if that feature
is available in Stylish or not.

The userstyle can be installed via userstyles.org ([https://userstyles.org/styles/156692/tdx-improved](https://userstyles.org/styles/156692/tdx-improved))
and the latest version will always be available there.

---

#### :calendar: Future Plans

I intend to turn this into a browser extension which will inject the styles (removing the need for
Stylish, Stylus or any other 3rd party extensions) and will also use JS to add some additional
client-side functionality to TDX. This will all happen as I need and as I get to it, no timetable
for these enhancements currently.

---

### License

MIT License

Copyright (c) 2018 Mike Sprague

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fmikesprague%2Ftdx-improved.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fmikesprague%2Ftdx-improved?ref=badge_large)