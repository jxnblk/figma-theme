
# figma-theme

Generate development-ready theme JSON files from Figma Styles

- Parse [Styles][] from a Figma file ID
- Works with [Styled System][] and other CSS-in-JS setups
- Built with [figma-js][]

```sh
npm i figma-theme
```

## Getting Started

1. Install `figma-theme` as a dev dependency in your project
2. Get a [personal access token][token] for the Figma API
3. Create a `.env` file with your access token
  - `FIGMA_TOKEN=<personal-access-token>`
  - Alternatively add an environment variable for `FIGMA_TOKEN`
4. Add an npm run script: `figma-theme <figma-file-id>`
5. Run the script to create a `theme.json` file based on Figma Styles

## Options

Options can be passed as CLI flags or included in a `figma-theme` object in your `package.json`

- `--out-dir`: output directory (default current working directory)
- `--metadata`: include additional metadata from the Figma API

[Styles]: https://help.figma.com/properties-panel/styles
[Styled System]: https://jxnblk.com/styled-system
[token]: https://www.figma.com/developers/docs#auth-dev-token
[figma-js]: https://github.com/jongold/figma-js

<!--
- TRi6YSk76405ImoatoMF1u28
- 2aMG4hw2qp3jSTGmtAMyhZ
- JGLoPfwRFqCwn4xZ8wUmSwp7
-->
