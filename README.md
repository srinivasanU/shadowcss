# What is this?

Get shadows for your design

# Installation

`npm i shadowdesign --save`

Then...

```
import { shadowcss } from 'shadowdesign';

shadowcss({
      shadow_type: 'soft',
      padding: false
});

<div class="shadowcss"></div>
```

# Options

Shadowcss supports 2 options, both of which are optional:

* *shadow_type* - _hard / soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)