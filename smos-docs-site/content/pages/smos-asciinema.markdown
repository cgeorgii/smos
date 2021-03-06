---
title: The Smos ASCIInema Automation Tool
---

This tool exists to automate smos casts for documentation purposes.
You can use it to produce a cast this:

<script
  id="asciicast-348778"
  src="https://asciinema.org/a/348778.js"
  async
  data-autoplay="true"
  data-loop="1"
  data-cols="80"
  data-rows="25">
  </script>

from a spec like this:

```
command: smos example.smos
file: example.smos
input:
- send: e
- wait: 1000
- type: Hello world!
- wait: 1000
- send: "\e"
- wait: 1000
- send: 'q'
- wait: 1000
```

See [the examples](https://github.com/NorfairKing/smos/tree/master/smos-asciinema/examples) in the source code.
