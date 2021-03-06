# a11y-syntax-highlighting

Accessible light and dark themes for the [Prism.js](http://prismjs.com/) syntax highlighting library.


## a11y-dark

![The a11y-dark theme being applied to the HTML of the Prism.js website. Screenshot.](https://raw.githubusercontent.com/ericwbailey/a11y-prism-theme/master/images/a11y-dark.png)

- Light text on a dark background.
- Background color of `#2b2b2b`.
- [WCAG AAA compliant](https://www.w3.org/TR/WCAG/#visual-audio-contrast-contrast) for color contrast.

| Color | Hex | Ratio | Normal Text | Large Text |
| :---- | :-- | ----: | :---------- | :--------- |
| [Bright Turquoise](http://chir.ag/projects/name-that-color/#00E0E0) | `#00e0e0` | [8.59:1](https://webaim.org/resources/contrastchecker/?fcolor=00E0E0&bcolor=2B2B2B) | AAA | AAA |
| [Chino](http://chir.ag/projects/name-that-color/#D4D0AB) | `#d4d0ab` | [9.04:1](https://webaim.org/resources/contrastchecker/?fcolor=D4D0AB&bcolor=2B2B2B) | AAA | AAA |
| [Conifer](http://chir.ag/projects/name-that-color/#ABE338) | `#abe338` | [9.29:1](https://webaim.org/resources/contrastchecker/?fcolor=ABE338&bcolor=2B2B2B) | AAA | AAA |
| [Gold](http://chir.ag/projects/name-that-color/#FFD700) | `#ffD700` | [10.09:1](https://webaim.org/resources/contrastchecker/?fcolor=FFD700&bcolor=2B2B2B) | AAA | AAA |
| [Spring Wood](http://chir.ag/projects/name-that-color/#F8F8F2) | `#f8f8f2` | [13.28:1](https://webaim.org/resources/contrastchecker/?fcolor=F8F8F2&bcolor=2B2B2B) | AAA | AAA |
| [Vivid Tangerine](http://chir.ag/projects/name-that-color/#FFA07A) | `#ffa07a` | [7.12:1](https://webaim.org/resources/contrastchecker/?fcolor=FFA07A&bcolor=2B2B2B) | AAA | AAA |


## a11y-light

![The a11y-light theme being applied to the HTML of the Prism.js website. Screenshot.](https://raw.githubusercontent.com/ericwbailey/a11y-prism-theme/master/images/a11y-light.png)

- Dark text on a light background.
- Background color of `#fefefe`.
- [WCAG AA compliant](https://www.w3.org/TR/WCAG/#visual-audio-contrast-contrast) for color contrast. WCAG AAA compliance forces the values on a light background to be too similar to each other to be used effectively for syntax highlighting.

| Color | Hex | Ratio | Normal Text | Large Text |
| :---- | :-- | ----: | :---------- | :--------- |
| [Chelsea Gem](http://chir.ag/projects/name-that-color/#AA5D00) | `#aa5d00` | [4.87:1](d) | AA | AAA |
| [Deep Cerulean](http://chir.ag/projects/name-that-color/#007FAA) | `#007faa` | [4.51:1](https://webaim.org/resources/contrastchecker/?fcolor=007FAA&bcolor=FEFEFE) | AA | AAA |
| [Dove Gray](http://chir.ag/projects/name-that-color/#696969) | `#696969` | [5.44:1](https://webaim.org/resources/contrastchecker/?fcolor=696969&bcolor=FEFEFE) | AA | AAA |
| [Emperor](http://chir.ag/projects/name-that-color/#545454) | `#545454` | [7.51:1](https://webaim.org/resources/contrastchecker/?fcolor=545454&bcolor=FEFEFE) | AAA | AAA |
| [Japanese Laurel](http://chir.ag/projects/name-that-color/#008000) | `#008000` | [5.09:1](https://webaim.org/resources/contrastchecker/?fcolor=008000&bcolor=FEFEFE) | AA | AAA |
| [Thunderbird](http://chir.ag/projects/name-that-color/#D91E18) | `#d91e18` | [5.02:1](https://webaim.org/resources/contrastchecker/?fcolor=D91E18&bcolor=FEFEFE) | AA | AAA |


## High Contrast Mode

Both themes have enhanced support for [Windows High Contrast Mode](https://support.microsoft.com/en-us/help/13862/windows-use-high-contrast-mode):

![The a11y-dark theme responding to Windows High Contrast Mode. Screenshot.](https://raw.githubusercontent.com/ericwbailey/a11y-prism-theme/master/images/a11y-high-contrast-mode.png)


## Thanks
- [Lea Verou](http://lea.verou.me/), for making the awesome Prism.js library.
- Michael Ball, for the idea.
