# Third-party notices

This project redistributes the third-party software listed below. Each license is reproduced in full.

The upstream single-file build bundles three.js **without** its required copyright and permission
notice. That notice is restored here, which is one of the reasons this mirror exists.

---

## three.js (r180)

three.js is bundled, minified, inside the inline `<script>` in `index.html`. It is not a separate
file, so the notice is reproduced here instead of as a file header.

- Project: https://github.com/mrdoob/three.js
- Revision: r180 (confirmed via the bundle's internal `REVISION` constant)
- License: MIT

```
The MIT License

Copyright © 2010-2025 three.js authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

---

## Fonts

Three families are used by the interface. All three are licensed under the
**SIL Open Font License, Version 1.1**, whose full text is in [`fonts/OFL.txt`](fonts/OFL.txt).

| Family | Weights used | Copyright |
|---|---|---|
| Big Shoulders Display | 500, 700, 900 | Copyright 2019 The Big Shoulders Project Authors (https://github.com/xotypeco/big_shoulders) |
| IBM Plex Mono | 400, 500 | Copyright © 2017 IBM Corp. with Reserved Font Name "Plex" |
| Barlow Condensed | 400, 500, 600 | Copyright 2017 The Barlow Project Authors (https://github.com/jpt/barlow) |

Upstream loaded these from the Google Fonts CDN at runtime. They are self-hosted here under
`fonts/`, so the page makes no third-party requests. See the README for why.

---

## The game itself

Not third-party software in the usual sense, and **not covered by any of the licenses above**.
See [`COPYRIGHT.md`](COPYRIGHT.md).
