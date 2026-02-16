# css-font-style

Functional CSS for font-style

## Filesize

| File | Size |
|------|------|
| `dist/font-style.css` | 581 bytes |
| `dist/font-style.min.css` | 405 bytes (143 Gzipped) |

## Install

```sh
npm install css-font-style
```

## Usage

### Import

```css
@import "css-font-style";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-font-style/dist/font-style.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-font-style/dist/font-style.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.fsn` | `font-style: normal;` |
| `.i` | `font-style: italic;` |
| `.oblique` | `font-style: oblique;` |
| `.fsn-s` | `font-style: normal;` |
| `.i-s` | `font-style: italic;` |
| `.oblique-s` | `font-style: oblique;` |
| `.fsn-m` | `font-style: normal;` |
| `.i-m` | `font-style: italic;` |
| `.oblique-m` | `font-style: oblique;` |
| `.fsn-l` | `font-style: normal;` |
| `.i-l` | `font-style: italic;` |
| `.oblique-l` | `font-style: oblique;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.fsn-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/font-style.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/font-style.css` — formatted
- `dist/font-style.min.css` — minified

## License

MIT
