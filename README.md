# SK Hand

A handwritten font crafted from real handwriting. SK Hand brings a personal, human touch to your projects with an authentic hand-lettered feel.

![SK Hand Font Specimen](documentation/specimen.png)

## About

SK Hand is an open-source handwritten font created by **Supriya Khanna**. It was made by converting natural handwriting into a digital typeface using [Ductus](https://www.ductus.app/).

- **Style:** Regular
- **Weight:** 400 (Regular)
- **Version:** 1.000
- **Glyphs:** 99
- **Character set:** Basic Latin (A–Z, a–z, 0–9), punctuation, common symbols, and typographic extras (smart quotes, en/em dashes, ellipsis)

## Preview

```
ABCDEFGHIJKLMNOPQRSTUVWXYZ
abcdefghijklmnopqrstuvwxyz
0123456789
!@#$%^&*()_+-=[]{}|;:'",.<>?/
```

## Download & Installation

### Download

Grab the latest release from the [Releases](../../releases) page, or download directly from the [`fonts/`](fonts/) directory.

| Format | File | Use Case |
|--------|------|----------|
| OTF | [`SKHand-Regular.otf`](fonts/otf/SKHand-Regular.otf) | Desktop apps (macOS, Windows, Linux) |
| TTF | [`SKHand-Regular.ttf`](fonts/ttf/SKHand-Regular.ttf) | Desktop apps, Android, older systems |
| WOFF2 | [`SKHand-Regular.woff2`](fonts/woff2/SKHand-Regular.woff2) | Web (modern browsers) |

### Install on your system

- **macOS:** Double-click the `.otf` or `.ttf` file and click "Install Font"
- **Windows:** Right-click the `.otf` or `.ttf` file and select "Install"
- **Linux:** Copy the font file to `~/.local/share/fonts/` and run `fc-cache -fv`

### Use on the web

Add this to your CSS:

```css
@font-face {
  font-family: 'SK Hand';
  src: url('fonts/woff2/SKHand-Regular.woff2') format('woff2'),
       url('fonts/ttf/SKHand-Regular.ttf') format('truetype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

body {
  font-family: 'SK Hand', cursive;
}
```

## Character Coverage

| Range | Characters |
|-------|-----------|
| Basic Latin uppercase | A B C D E F G H I J K L M N O P Q R S T U V W X Y Z |
| Basic Latin lowercase | a b c d e f g h i j k l m n o p q r s t u v w x y z |
| Digits | 0 1 2 3 4 5 6 7 8 9 |
| Punctuation & symbols | `! " # $ % & ' ( ) * + , - . / : ; < = > ? @ [ \ ] ^ _ \` { \| } ~` |
| Typographic extras | non-breaking space, hyphen (‐), non-breaking hyphen (‑), en dash (–), em dash (—), smart quotes (' ' " "), ellipsis (…), minus sign (−) |

## Repository Structure

```
SK-Hand/
├── fonts/
│   ├── otf/                    # OpenType font files
│   │   └── SKHand-Regular.otf
│   ├── ttf/                    # TrueType font files
│   │   └── SKHand-Regular.ttf
│   └── woff2/                  # Web font files
│       └── SKHand-Regular.woff2
├── documentation/
│   └── FONTLOG.txt             # Font changelog
├── LICENSE                     # SIL Open Font License 1.1
└── README.md
```

## License

SK Hand is licensed under the [SIL Open Font License, Version 1.1](LICENSE).

This means you are free to:
- **Use** the font in any project (personal, commercial, print, web, apps)
- **Modify** the font and create derivative works
- **Distribute** the font, bundled with software or on its own (but not sold standalone)

## Contributing

Contributions are welcome! If you'd like to improve SK Hand:

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/add-glyphs`)
3. Commit your changes (`git commit -m 'Add new glyphs for extended Latin'`)
4. Push to the branch (`git push origin feature/add-glyphs`)
5. Open a Pull Request

### Ideas for contributions

- Extending character coverage (accented Latin, Cyrillic, etc.)
- Adding font weights (Bold, Light, etc.)
- Improving kerning and spacing
- Creating an italic variant

## Credits

- **Designer:** Supriya Khanna
- **Tool:** [Ductus](https://www.ductus.app/) — handwriting to font converter
