# Moneyou

**Moneyou media for the WordPress payment processing library.**

## Colors

### Moneyou Crimson

**WEB:** `#d40d47`

*	http://www.color-hex.com/color/d40d47
*	https://www.htmlcsscolor.com/hex/d40d47

### Moneyou Summer Sky

**WEB:** `#2aabce`

*	http://www.color-hex.com/color/2aabce
*	https://www.htmlcsscolor.com/hex/2aabce

### Moneyou Governor Bay

**WEB:** `#555390`

*	http://www.color-hex.com/color/555390
*	https://www.htmlcsscolor.com/hex/555390

## Links

*	https://developer.apple.com/library/archive/qa/qa1686/_index.html
*	https://stackoverflow.com/questions/9853325/how-to-convert-a-svg-to-a-png-with-image-magick

## `svgexport`

```bash
svgexport svgexport.json
```

```bash
inkscape --export-png=/Users/remco/Projects/moneyou/converted/inkscape/png/moneyou-logo-600x300-10pct-margin/moneyou-logo-600x300-10pct-margin.png --export-width=600 --export-height=300 /Users/remco/Projects/moneyou/src/Logo-600x300-10pct-margin.svg
inkscape --export-png=/Users/remco/Projects/moneyou/converted/inkscape/png/moneyou-logo-600x300-10pct-margin/moneyou-logo-600x300-10pct-margin@2x.png --export-width=1200 --export-height=600 /Users/remco/Projects/moneyou/src/Logo-600x300-10pct-margin.svg
```

```bash
convert -background transparent -size 600x300 src/Logo-600x300-10pct-margin.svg converted/imagemagick/png/moneyou-logo-600x300-10pct-margin/moneyou-logo-600x300-10pct-margin.png
convert -background transparent -size 1200x600 src/Logo-600x300-10pct-margin.svg converted/imagemagick/png/moneyou-logo-600x300-10pct-margin/moneyou-logo-600x300-10pct-margin@2x.png
```

```bash
rsvg-convert -w 600 -h 300 src/Logo-600x300-10pct-margin.svg -o converted/rsvg/png/moneyou-logo-600x300-10pct-margin/moneyou-logo-600x300-10pct-margin.png
rsvg-convert -w 1200 -h 600 src/Logo-600x300-10pct-margin.svg -o converted/rsvg/png/moneyou-logo-600x300-10pct-margin/moneyou-logo-600x300-10pct-margin@2x.png
rsvg-convert -w 1800 -h 900 src/Logo-600x300-10pct-margin.svg -o converted/rsvg/png/moneyou-logo-600x300-10pct-margin/moneyou-logo-600x300-10pct-margin@3x.png
rsvg-convert -w 2400 -h 1200 src/Logo-600x300-10pct-margin.svg -o converted/rsvg/png/moneyou-logo-600x300-10pct-margin/moneyou-logo-600x300-10pct-margin@4x.png
```
