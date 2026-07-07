# @kevinschaul/theme

Shared Astro theme components and styles for kschaul.com-style projects.

## Exports

- `@kevinschaul/theme/components/BaseLayout.astro`
- `@kevinschaul/theme/components/Header.astro`
- `@kevinschaul/theme/components/Footer.astro`
- `@kevinschaul/theme/styles/tokens.css`
- `@kevinschaul/theme/styles/base.css`

## Usage

Install the package from GitHub, then import the shared components and CSS from
the package exports.

```astro
---
import BaseLayout from "@kevinschaul/theme/components/BaseLayout.astro"
import Header from "@kevinschaul/theme/components/Header.astro"
import Footer from "@kevinschaul/theme/components/Footer.astro"
import "@kevinschaul/theme/styles/tokens.css"
import "@kevinschaul/theme/styles/base.css"
---
```
