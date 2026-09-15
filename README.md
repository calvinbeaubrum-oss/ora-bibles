# Ora Bibles - By Language

Bible database for the Ora app, organized **by language**.

**209** JSON files | **56** languages | **69** deuterocanonical texts

## Structure

```
lang/
  <language-code>/
    <Translation>.json      # Canonical Bible
    deuterocanonical/       # (en) deuterocanonical texts
    README.md               # Translation list
metadata/
  books_metadata.json       # Full catalog
  categories.json           # canonical / deuterocanonical / apocryphal
  cross_references/         # 7 cross-reference shards
```

## Languages

| Language | Translations |
|----------|--------------|
| `bea` | 1 |
| `ceb` | 1 |
| `chr` | 1 |
| `cop-sa` | 1 |
| `cs` | 2 |
| `cu` | 1 |
| `da` | 1 |
| `de` | 12 |
| `el` | 1 |
| `en` | 34 + 69 deuterocanonical |
| `enm` | 1 |
| `eo` | 1 |
| `es` | 4 |
| `et` | 1 |
| `fi` | 3 |
| `fr` | 11 |
| `got` | 1 |
| `grc` | 3 |
| `gv` | 1 |
| `hbo` | 3 |
| `he` | 1 |
| `hr` | 1 |
| `ht` | 1 |
| `hu` | 1 |
| `hy` | 1 |
| `ja` | 3 |
| `ko` | 2 |
| `la` | 5 |
| `lv` | 1 |
| `lzh` | 1 |
| `mg` | 1 |
| `mi` | 1 |
| `mlf` | 1 |
| `my` | 1 |
| `nb` | 1 |
| `nl` | 3 |
| `nn` | 1 |
| `pl` | 2 |
| `pon` | 1 |
| `pt` | 3 |
| `ru` | 2 |
| `sl` | 4 |
| `sml` | 1 |
| `sq` | 1 |
| `sr` | 2 |
| `sv` | 3 |
| `syr` | 1 |
| `th` | 1 |
| `tl` | 1 |
| `tlh` | 1 |
| `tpi` | 1 |
| `tsg` | 1 |
| `uk` | 1 |
| `vi` | 1 |
| `vls` | 1 |
| `zh-hant` | 2 |

## Categories

- **Canonical** (73 books): Old + New Testament
- **Deuterocanonical** (7 books): Tobit, Judith, 1-2 Maccabees, Wisdom, Sirach, Baruch
- **Apocryphal**: Not recognized by the Church - labeled, not downloadable in Ora

## Sources

- [scrollmapper/bible_databases](https://github.com/scrollmapper/bible_databases) - 140 translations
- [scrollmapper/bible_databases_deuterocanonical](https://github.com/scrollmapper/bible_databases_deuterocanonical)
- [scrollmapper/book_list](https://github.com/scrollmapper/book_list) - index

## JSON Format

```json
{
  "translation": "KJV: King James Version",
  "books": [{
    "name": "Genesis",
    "chapters": [{
      "chapter": 1,
      "verses": [{ "verse": 1, "text": "In the beginning..." }]
    }]
  }]
}
```

## License

MIT
