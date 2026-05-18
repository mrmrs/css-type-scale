# css-type-scale

Functional CSS for type-scale

## Filesize

| File | Size |
|------|------|
| `dist/type-scale.css` | 963 bytes |
| `dist/type-scale.min.css` | 629 bytes (200 Gzipped) |

## Install

```sh
npm install css-type-scale
```

## Usage

### Import

```css
@import "css-type-scale";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-type-scale/dist/type-scale.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-type-scale/dist/type-scale.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.f1` | `font-size: 2rem;` |
| `.f2` | `font-size: 1.5rem;` |
| `.f4` | `font-size: 1.2rem;` |
| `.f5` | `font-size: 1rem;` |
| `.small` | `font-size: .85rem;` |
| `.mega-s` | `font-size: 3rem;` |
| `.f1-s` | `font-size: 2rem;` |
| `.f2-s` | `font-size: 1.5rem;` |
| `.f4-s` | `font-size: 1.2rem;` |
| `.f5-s` | `font-size: 1rem;` |
| `.f6-s` | `font-size: .85rem;` |
| `.mega-m` | `font-size: 3rem;` |
| `.f1-m` | `font-size: 2rem;` |
| `.f2-m` | `font-size: 1.5rem;` |
| `.f4-m` | `font-size: 1.2rem;` |
| `.f5-m` | `font-size: 1rem;` |
| `.f6-m` | `font-size: .85rem;` |
| `.mega-l` | `font-size: 4rem;` |
| `.f1-l` | `font-size: 3rem;` |
| `.f2-l` | `font-size: 2rem;` |
| `.f3-l` | `font-size: 1.5rem;` |
| `.f4-l` | `font-size: 1.2rem;` |
| `.f6-l` | `font-size: 1rem;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.f1-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/type-scale.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/type-scale.css` — formatted
- `dist/type-scale.min.css` — minified

## License

MIT
