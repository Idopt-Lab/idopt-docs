# IDOpt Lab Documentation

Single documentation site for IDOpt Lab research software, built with [Mintlify](https://mintlify.com).

## How it works

Docs live next to the code. Each project repo keeps its own `docs/*.mdx`; a `sync-docs` GitHub Action in that repo copies changed pages into a subfolder here and rebuilds the navigation tab automatically. **Do not hand-edit the project subfolders in this repo** — edit `docs/` in the source repo instead.

| Site tab | Source repo |
|---|---|
| Regional Air Mobility | [regional-air-mobility-design-operations](https://github.com/Idopt-Lab/regional-air-mobility-design-operations) |
| Air Travel Model | [airTravelModel](https://github.com/Idopt-Lab/airTravelModel) |
| Web Visuals | [webVisuals](https://github.com/Idopt-Lab/webVisuals) |

Pages edited directly in this repo: `index.mdx` (home) and `docs.json` (site config).

## Local preview

```
npm i -g mint
mint dev
```
