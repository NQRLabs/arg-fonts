# Pigpen Cipher Font

A handcrafted cipher font based on the classic Pigpen (Freemason) cipher, also known as the Masonic cipher or tic-tac-toe cipher.

## Specimen

![Pigpen Cipher Specimen](specimen/pigpen-specimen.png)

## Features

- **Complete alphabet mapping** - A-Z mapped to Pigpen cipher symbols
- **Traditional grid system** - Based on the classic 3x3 and X grids
- **Web-optimized formats** - Available in TTF, OTF, and WOFF2
- **Clean geometric design** - Clear, legible cipher symbols

## History

The Pigpen cipher (also known as the Freemason cipher or tic-tac-toe cipher) is a simple substitution cipher that replaces letters with geometric symbols. It was used by the Freemasons in the 18th century to keep their records private, though its origins may be even older.

The cipher uses two grids: a 3x3 grid (like tic-tac-toe) containing the letters A-I, and an X-shaped grid containing J-R. Dots are added to represent the letters S-Z using the same pattern. Each letter is represented by the portion of the grid that surrounds it, making it look like letters are trapped in "pigpens."

This font has been used throughout history in various secret societies, escape maps during wars, and modern ARGs and puzzle hunts. It remains a popular cipher for introducing cryptography concepts due to its visual and memorable nature.

## Usage

### Desktop Installation

1. Download the font file:
   - **Windows/Linux:** Use `Pigpen-Regular.ttf`
   - **macOS:** Use `Pigpen-Regular.otf`
2. Double-click the file and click "Install"
3. The font will be available as "Pigpen" in your applications

### Web Usage

Copy the `@font-face` declaration from `css/fontface.css` into your stylesheet, or link directly to the CSS file:

```html
<link rel="stylesheet" href="path/to/css/fontface.css">
```

Then use in your CSS:

```css
.cipher-text {
  font-family: 'Pigpen', monospace;
  font-size: 24px;
}
```

## Character Map

### Grid 1 (3x3 - No Dots)
```
┌─┬─┬─┐
│A│B│C│
├─┼─┼─┤
│D│E│F│
├─┼─┼─┤
│G│H│I│
└─┴─┴─┘
```

### With Dots (Grid 1 repeated)
```
J K L (A B C with dots)
M N O (D E F with dots)
P Q R (G H I with dots)
```

### Grid 2 (X Shape - No Dots)
```
    S  
   \ /
 T  X  U
   / \
    V  
```

### With Dots (Grid 2 repeated)
```
W X Y Z (S T U V with dots)
```

## Reserved Font Name

"Pigpen" is the reserved font name for this typeface. Modified versions must use a different name.

## License

This font is licensed under the SIL Open Font License 1.1. See [OFL.txt](OFL.txt) for full license text.

## Created With

This font was created using [Calligraphr](https://www.calligraphr.com), a web-based tool for creating custom fonts from your own handwriting or designs.

## Author

Created by NQR for the NQR Labs ARG toolkit.
https://nqrlabs.com

## Version

Current version: 1.0.0 (2025)
