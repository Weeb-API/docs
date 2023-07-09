---
permalink: /carbon
layout: page
title: Carbon Parameters
---

---
### Query/Body Parameters

| parameter              | default                    | type                      | description                                                                                                                                                             |
| ---------------------- | -------------------------- | ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `code` (required)      |                            | string                    | code snippet                                                                                                                                                            |
| `backgroundColor`      | `"rgba(171, 184, 195, 1)"` | string                    | hex or rgba color                                                                                                                                                       |
| `dropShadow`           | `true`                     | boolean                   | turn on/off shadow                                                                                                                                                      |
| `dropShadowBlurRadius` | `"68px"`                   | string                    | shadow blur radius                                                                                                                                                      |
| `dropShadowOffsetY`    | `"20px"`                   | string                    | shadow offset y                                                                                                                                                         |
| `exportSize`           | `"2x"`                     | string                    | resolution of exported image, e.g. `1x`, `3x`                                                                                                                           |
| `fontCustom`           | `""`                       | string                    | custom woff font's contents, encoded in base64                                                                                                                          |
| `fontSize`             | `"14px"`                   | string                    | font size                                                                                                                                                               |
| `fontFamily`           | `"Hack"`                   | string                    | font family, e.g. `JetBrains Mono`, `Fira Code`. See all names in carbon.(Click gear → `misc` → `export config` for downloading JSON with the current setting)                    |
| `firstLineNumber`      | `1`                        | number                    | first line number                                                                                                                                                       |
| `language`             | `"auto"`                   | string                    | programing language for properly highlighting. See name in carbon. (Click gear → `misc` → `export config` for downloading JSON with the current setting) For example bash is named `"application/x-sh"` |
| `lineHeight`           | `"133%"`                   | string                    | line height                                                                                                                                                             |
| `lineNumbers`          | `false`                    | boolean                   | turn on/off line number                                                                                                                                                 |
| `paddingHorizontal`    | `"56px"`                   | string                    | horizontal padding                                                                                                                                                      |
| `paddingVertical`      | `"56px"`                   | string                    | vertical padding                                                                                                                                                        |
| `prettify`             | `false`                    | boolean                   | prettify code with prettier. It works with javascript snippets only, like in carbon.                                                                                    |
| `theme`                | `"seti"`                   | string                    | code theme                                                                                                                                                              |
| `watermark`            | `false`                    | boolean                   | turn on/off watermark                                                                                                                                                   |
| `width`                | `536`                      | number                    | specify the width of the screenshot                                                                                                                                     |
| `widthAdjustment`      | `true`                     | boolean                   | turn on/off width adjustment                                                                                                                                            |
| `windowControls`       | `true`                     | boolean                   | turn on/off window controls                                                                                                                                             |
| `windowTheme`          | `"none"`                   | `"none"` `"sharp"` `"bw"` | window theme                                                                                                                                                            |

**Defaults params** are the same as https://carbon.now.sh.

**Response** is an image of a code snippet.

---
