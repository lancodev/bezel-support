---
title: Bezel third-party notices
---

# Third-party notices

Bezel includes or is derived from the following open-source software. Each component is used under its own license, reproduced or referenced below.

## Plugin (JavaScript)

| Component | License |
|---|---|
| @elgato/streamdeck, @elgato/utils, @elgato/schemas (Corsair Memory Inc.) | MIT |
| sdpi-components (Corsair Memory Inc. and contributors) | MIT |
| Lit (Google LLC) | BSD-3-Clause |
| ws (Einar Otto Stangvik and contributors) | MIT |
| tslib (Microsoft Corporation) | 0BSD |

## DDC helper (Rust)

| Component | License |
|---|---|
| serde, serde_json | MIT OR Apache-2.0 (used under MIT) |
| ddc, ddc-i2c, ddc-winapi, i2c-linux (arcnmx) | MIT |
| edid (emersion) | MIT |
| nom (Geoffroy Couprie) | MIT |

## Ported logic

The macOS DDC/CI backend reimplements algorithms and protocol constants from:

- **m1ddc**, Copyright (c) 2021 waydabber (MIT)
- **MonitorControl** (`Arm64DDC.swift`), Copyright (c) MonitorControl contributors, including @JoniVR, @theOneyouseek and @waydabber (MIT)
- **AppleSiliconDDC**, Copyright (c) waydabber (MIT), used as a reference

## MIT License

> Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## BSD 3-Clause License (Lit)

> Copyright 2019 Google LLC. Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met: (1) Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer. (2) Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution. (3) Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.
>
> THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

## 0BSD License (tslib)

> Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted. THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE.
