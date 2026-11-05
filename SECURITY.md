# Security policy

## Design

- The visual declares `"privileges": []`: no web access, no local storage, no file export.
- It makes no network requests and loads no external scripts, fonts or images.
- Text from report data is rendered with `textContent` only; the build lint rules (`eslint-plugin-powerbi-visuals`) forbid `innerHTML`, `eval` and similar.
- The sample semantic model has no external data source or credentials.

## Reporting a vulnerability

Please do not open a public issue for security problems. Email **contact@faizaan.me** with a description and steps to reproduce. You should get a reply within a few working days.
