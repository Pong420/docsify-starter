## Docsify Starter

This documents are produce by [docsify](https://docsify.js.org/#/).

<br />

To enable live reload run

```bash
yarn dev
# with custom port
yarn dev --port 5000
```

<br />

### Plugins

List of plugins that used

- [docsify-darklight-theme](https://github.com/boopathikumar018/docsify-darklight-theme) - The main styles of this document. With some customized style handled in `docs/js/darklightTheme.js` and `docs/assets/style.css`

- [Prism](https://prismjs.com/) - Used by docsify for code block. There are some extra prism components/plugins added

  - `prism-bash`
  - `prism-json`
  - `prism-typescript`
  - `prism-line-highlight`

- [docsify-pagination](https://github.com/imyelo/docsify-pagination) - Add page navigation components at footer

- [mermaid-docsify](https://github.com/Leward/mermaid-docsify) - Enable [mermaid](https://github.com/mermaid-js/mermaid) in docsify. It is a diagramming and charting tool that uses Markdown-inspired text definitions.

- `docs/js/scrollbar.js` - Change scrollbar style of MS Window browser
- `docs/js/markdown.js` - Add file and line highlight in code block

### Code Block

```md file=docs/js/markdown.js
Code block with file name
```

```md file=docs/js/markdown.js highlight=1-2,3
line highlight by metadata - 1
line highlight by metadata - 2
line highlight by metadata - 3

line highlight by comment - 1 <!-- highlight-line  -->

line highlight by comment - 2 <!-- highlight-line  -->
```
