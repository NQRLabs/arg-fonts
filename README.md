# NQR Labs ARG Cipher Fonts

A curated collection of handcrafted cipher fonts designed for alternate reality games (ARGs), puzzle hunts, cryptography education, and mystery storytelling.

## Font Gallery

### Zodiac Cipher
![Zodiac Cipher](ZodiacCipher/specimen/zodiac-specimen.png)

Based on the infamous cipher symbols used by the Zodiac Killer in his cryptographic messages. Includes authentic symbol mappings from both solved and unsolved ciphers.

**[View Details](ZodiacCipher/README.md)** | **[Download](ZodiacCipher/fonts/)**

---

### Pigpen Cipher
![Pigpen Cipher](PigpenCipher/specimen/pigpen-specimen.png)

The classic Freemason cipher (also known as the Masonic cipher or tic-tac-toe cipher). Features the traditional grid-based geometric symbol system used by secret societies since the 18th century.

**[View Details](PigpenCipher/README.md)** | **[Download](PigpenCipher/fonts/)**

---

### Falls Cipher
![Falls Cipher](FallsCipher/specimen/fallscipher-specimen.png)

Mystery-themed symbol substitution cipher inspired by cryptographic puzzles in adventure media. First in a planned series covering various symbol cipher systems.

**[View Details](FallsCipher/README.md)** | **[Download](FallsCipher/fonts/)**

---

## How to Use

### For Desktop Applications

1. **Choose your font** from the gallery above
2. **Download the appropriate format:**
   - **Windows/Linux:** Use `.ttf` files
   - **macOS:** Use `.otf` files
3. **Install the font:**
   - Double-click the downloaded file
   - Click "Install Font" in the dialog
4. **Use in your applications:**
   - Open any text editor, design tool, or word processor
   - Select the font from your font menu
   - Type normally - letters A-Z will display as cipher symbols

### For Web Projects

Each font includes a ready-to-use `css/fontface.css` file. To use on the web:

**Option 1: Link the CSS file**
```html
<link rel="stylesheet" href="path/to/FontName/css/fontface.css">

<p class="cipher-text">Hello World</p>
```

**Option 2: Copy the @font-face declaration**
```css
@font-face {
  font-family: 'Zodiac';
  src: url('fonts/Zodiac-Regular.woff2') format('woff2'),
       url('fonts/Zodiac-Regular.otf') format('opentype');
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}

.cipher-text {
  font-family: 'Zodiac', monospace;
  font-size: 24px;
}
```

**Note:** For web use, the `.woff2` format provides the best compression and performance.

### For ARG & Puzzle Design

These fonts are specifically designed for:
- **Cipher puzzles** - Create encoded messages that require decryption
- **Alternate reality games** - Hide clues in plain sight using cipher text
- **Escape rooms** - Design puzzles with authentic-looking cipher documents
- **Educational materials** - Teach cryptography concepts with real cipher alphabets
- **Mystery storytelling** - Add atmospheric cipher text to narratives

**Pro tip:** Combine with `white-space: pre;` in CSS to preserve spacing for grid-based ciphers like Pigpen.

## Creating Your Own Fonts

All fonts in this collection were created using **[Calligraphr](https://www.calligraphr.com)**, a powerful web-based tool that converts your handwriting or custom designs into working fonts.

### Why Calligraphr?

- ✅ **No software installation** - Works entirely in your browser
- ✅ **Simple workflow** - Print templates, draw glyphs, upload, generate font
- ✅ **Multiple formats** - Exports TTF, OTF, and WOFF formats
- ✅ **Free tier available** - Create fonts with up to 75 characters
- ✅ **Pro features** - Ligatures, kerning, multiple variants for handwriting randomization

### How to Create a Cipher Font

1. **Design your cipher alphabet** - Map each letter A-Z to a unique symbol
2. **Visit [Calligraphr](https://www.calligraphr.com)** and create an account
3. **Download a template** - Calligraphr provides printable glyph templates
4. **Draw your symbols** - Fill in the template with your cipher glyphs
5. **Upload and generate** - Calligraphr processes your drawings into a font
6. **Download and test** - Install the font and try it in a text editor

**Resources:**
- Calligraphr Tutorials: https://www.calligraphr.com/en/docs/
- Font creation guide: https://www.calligraphr.com/en/docs/tutorial1/

### Generate Professional Specimens

Once you've created your font, use our **[Specimen Generator](specimen.html)** to create beautiful specimen images:

1. Upload your font file (TTF, OTF, WOFF, or WOFF2)
2. Edit the font name and choose background color
3. Preview with full alphabet, numbers, and special characters
4. Download as PNG (1200x400px, ready for web galleries)

The specimen generator automatically shows:
- Font name in large cipher symbols (96px)
- Three-row layout: Uppercase (full width), Lowercase (full width), Numbers/Special (side-by-side)
- Complete character set with labeled sections
- Professional layout matching NQR Labs theme
- Optimized spacing for consistent single-line alphabets

## Font Specifications

| Font | Glyphs | Style | Formats | License |
|------|--------|-------|---------|---------|
| Zodiac Cipher | 26 letters + punctuation | Symbolic/Historical | TTF, OTF, WOFF2 | OFL 1.1 |
| Pigpen Cipher | 26 letters | Geometric | TTF, OTF, WOFF2 | OFL 1.1 |
| Falls Cipher | 26 letters | Symbolic/Mystery | TTF, OTF, WOFF2 | OFL 1.1 |

## License & Credits

### Open Font License

All fonts are released under the **SIL Open Font License 1.1**, which means:

✅ **Free to use** - Personal and commercial projects
✅ **Free to modify** - Create derivative works
✅ **Free to distribute** - Share with others
✅ **Free to bundle** - Include in software or websites
❌ **Cannot sell fonts alone** - Must be bundled with other software/content
❌ **Cannot use reserved names** - Modified versions must use different names

Full license text is included in each font's `OFL.txt` file.

### Reserved Font Names

The following names are reserved and may not be used for modified versions:
- "Zodiac" (Zodiac Cipher font)
- "Pigpen" (Pigpen Cipher font)
- "Falls Cipher" (Falls Cipher font)

### Attribution

Created by **NQR** for the NQR Labs ARG toolkit.

When using these fonts in public projects, attribution is appreciated but not required:
```
Fonts by NQR | https://nqrlabs.com/arg-fonts/
```

### Created With

These fonts were created using [Calligraphr](https://www.calligraphr.com) - a web-based custom font creator.

## Documentation

- **[PACK-README.md](PACK-README.md)** - Quick start download guide
- **[CHANGELOG.md](CHANGELOG.md)** - Version history for all fonts
- **Per-font documentation:**
  - [Zodiac Cipher Documentation](ZodiacCipher/README.md)
  - [Pigpen Cipher Documentation](PigpenCipher/README.md)
  - [Falls Cipher Documentation](FallsCipher/README.md)

## Version

Current pack version: **1.0.0** (2025-11-11)

See [CHANGELOG.md](CHANGELOG.md) for detailed version history.

## Support & Feedback

- **Issues & Suggestions:** https://github.com/NQRLabs/nqrlabs.github.io/issues
- **Website:** https://nqrlabs.com
- **Discord:** https://discord.gg/HT9YE8rvuN

## Related Tools

Looking for tools to use with these fonts?

- **[Carbbels](https://nqrlabs.com/Carbbels/)** - Anagram solver with draggable letter tiles
- **[GlyphGrid](https://nqrlabs.com/GlyphGrid/)** - Cryptogram solver with intelligent mapping
- **[Inknigma](https://nqrlabs.com/Inknigma/)** - Hide messages in images with steganography
- **[Veilocity](https://nqrlabs.com/Veilocity/)** - Motion-defined text video generator
- **[Zygnul](https://nqrlabs.com/Zygnul/)** - Glitch text generator with cipher font support

Browse all ARG tools at **[nqrlabs.com](https://nqrlabs.com)**

---

© 2025 NQR | Licensed under SIL Open Font License 1.1
