# darija-tech-glossary

Tech vocabulary in **English, French, and Moroccan Darija** — as data.

Moroccan developers switch between three languages all day: French at school, English in the docs, Darija everywhere else. This glossary collects the words that live in between, in a simple CSV anyone can extend.

## The data

[`glossary.csv`](glossary.csv) — one term per row:

| column | meaning |
| --- | --- |
| `english` | the term in English |
| `french` | the term in French |
| `darija_arabic` | the term in Darija (Arabic script) |
| `darija_latin` | the term in Darija (Latin script, as typed in chats) |
| `notes` | usage note — borrowed word, formal term, or both |

Example:

```csv
database,base de données,قاعدة المعطيات,qa3idat l-ma3loumat,formal term; most devs just say "la base"
```

## Why

- Study notes for Moroccan dev students
- A seed dataset for language tools (and a good test file for CSV profilers)

## Contributing

Add a row, keep the column order, keep it honest: if everyone actually says the French word in Darija conversation, say so in the notes.

## License

MIT — see [LICENSE](LICENSE).
