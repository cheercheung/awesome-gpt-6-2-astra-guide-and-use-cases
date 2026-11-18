# Maintenance

## Source of truth

The English README and `astra-usecase-curated.json` describe the same ordered cases. `astra-usecase-curated.md` is the compact index. The translated READMEs preserve case numbers, explicit anchors, original sources, creators, type/date metadata and media links.

## Case format

Use a stable `case-N` anchor, a source-linked H3 title with creator credit, one bold practical takeaway, readable source notes, the demonstration media and a final `Type: ... | Date: YYYY-MM-DD` line. Full prompts are optional; link the creator’s brief when available.

## Update checklist

1. Review every new concrete demo and merge duplicates by underlying work.
2. Add every qualifying work, without a selection cap.
3. Assign new cases the next available numbers. Place the latest batch first in the Menu, case section, and both indexes. Update English first, then sync the same order to all ten translations.
4. Use R2-hosted images or R2 posters linked to playable videos. Place separate comparison clips together.
5. Check all relative links, anchors, case counts, metadata, media URLs and translated text. Inspect desktop and narrow README layouts.
6. Honor source corrections and removal requests. Keep credentials and private working material out of commits.

## Validation

```sh
git diff --check
```

Before publication, compare all case records and README sections, verify public media loads and plays, and inspect the rendered GitHub page. At ten or more live stars, append Star History as the last README block; otherwise omit it.
