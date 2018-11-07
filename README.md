About
=======
cue-parser is an cue-sheet parser library written for nodejs.
Most of the code is inspired by [cue-go](https://github.com/vchimishuk/cue-go)

[![Build Status](https://travis-ci.com/gekowa/cue-parser.svg?branch=master)](https://travis-ci.org/justlaputa/cue-parser)

How to use
=======
Add dependency in your `package.json` file:

```bash
npm install cue-parser
```
or
```bash
npm install https://github.com/gekowa/cue-parser
```

use it in you node source code

```javascript
var parser = require('cue-parser');

var cuesheet = parser.parse('filename.cue');

console.log(cuesheet.performer);
console.log(cuesheet.files);
console.log(cuesheet.files[0].tracks);
```

References
==========

- [Cue sheet format kodi.wiki](http://kodi.wiki/view/Cue_sheets)
- [Cue sheet format from wiki.hydrogenaud.io](http://wiki.hydrogenaud.io/index.php?title=Cue_sheet)
