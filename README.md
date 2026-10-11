# Corvo public docs

Mintlify documentation in English and Traditional Chinese. English pages live at the repository root; their counterparts live under `zh-Hant/`. `docs.json` defines both navigation trees.

## Preview and validate

From this directory, use the Mintlify CLI:

```sh
npx mint dev
npx mint validate
npx mint broken-links
```

The current refresh was validated with Mintlify CLI `4.2.1006`.

## Editing

- Update the matching page in both languages and keep navigation in sync.
- Use actual interface labels in steps. Add a caption explaining what the reader should check in each screenshot.
- In Chinese prose, keep punctuation outside bold delimiters: `**確認**：...`. A closing delimiter after punctuation immediately followed by Chinese text may render literally.
- Check the rendered page as well as the MDX. Build validation alone does not catch every Markdown emphasis or image-cropping problem.
- Keep screenshots focused on the relevant controls. Mask credentials and private identifiers before committing.
- Record screenshot sources and diagram purposes in [assets/README.md](assets/README.md).
