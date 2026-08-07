# anyword

> [!IMPORTANT]
> **This repository has moved.** `anyword` now lives in the
> [**anyfamily**](https://github.com/kirilinsky/anyfamily) monorepo alongside the
> rest of the `any*` family. This copy is archived and frozen at v1 — anything
> below is kept for history only.

Text into locale-correct words, graphemes and sentences — count and truncate without ripping an emoji in half. One function over Intl.Segmenter.

|  |  |
| --- | --- |
| **Source** | [kirilinsky/anyfamily → packages/anyword](https://github.com/kirilinsky/anyfamily/tree/main/packages/anyword) |
| **Docs** | [anyfamily.site/docs/anyword](https://anyfamily.site/docs/anyword) |
| **Demo** | [anyfamily.site/anyword](https://anyfamily.site/anyword) |
| **npm** | [npmjs.com/package/anyword](https://www.npmjs.com/package/anyword) |

The package is still published and maintained — only the repository moved.
`npm install anyword` works exactly as before.

## v2 changed the API

Every `any*` package now exports **exactly one name**, with the extras hanging
off it:

```diff
- anywordCount(text)
+ anyword.count(text)
```

Full notes: [migrating to v2](https://anyfamily.site/docs/anyword#migrating).

## the rest of the family

Eight micro, zero-dependency Intl tools — one function each, zero data files,
200+ locales via native `Intl`. `anywhen` · `anyamount` · `anymany` ·
`anyaround` · `anylong` · `anyplural` · `anyword` · `anylocale`, or all eight
at once via [`anyfamily`](https://www.npmjs.com/package/anyfamily).

**[anyfamily.site](https://anyfamily.site)** · ⭐ [star the monorepo](https://github.com/kirilinsky/anyfamily)

MIT © [kirilinsky](https://github.com/kirilinsky)
