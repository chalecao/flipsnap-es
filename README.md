# flipsnap.js

[![Build Status](https://travis-ci.org/hokaccha/js-flipsnap.png?branch=master)](https://travis-ci.org/hokaccha/js-flipsnap)
[![Coverage Status](https://coveralls.io/repos/hokaccha/js-flipsnap/badge.png?branch=master)](https://coveralls.io/r/hokaccha/js-flipsnap?branch=master)

flipsnap.js is snap scroll for touch device.

http://hokaccha.github.com/js-flipsnap/

# usage
```
// install 
npm install flipsnap-es --save

// code 
import Flipsnap from 'flipsnap-es'
let flipsnap = Flipsnap(this.base.querySelector('.flipsnap'), {
    disableTouch: false
});

```

# fixed issue
1. after user finger off the device, then switch next or prev page, cause not smooth
