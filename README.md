# What is this?

Get shadows for your design

# Installation

`npm i shadowcss --save`

Then...

```
import { shadowcss } from 'shadowcss';

shadowcss({
      shadow_type: 'soft',
      padding: false
});
```

# Options

Shadowcss supports 2 options, both of which are optional:

* *shadow_type* - _hard / soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)