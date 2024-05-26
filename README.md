# Netlify Example Styles

Quickly apply some simple branding to Netlify examples and demos


## Usage

A minified CSS file is available to use directly in your sites by linking to this stylesheet URL. To ease the performance hit of sourcing the fonts from another domain via this CSS, we should preload those too

```html
<link rel="preload" href="https://example-styles.netlify.app/fonts/PacaembuVar-latin.woff2" as="font" type="font/woff2" />
<link rel="preload" href="https://example-styles.netlify.app/fonts/MulishVar-latin.woff2" as="font" type="font/woff2" />
<link rel="stylesheet" href="https://example-styles.netlify.app/styles.css">
```
