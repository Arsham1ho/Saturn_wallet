# Saturn Wallet — Browser Extension Build

A built browser-extension distribution of Saturn Wallet, stored in this
repository as a single archive: `Saturn_Wallet.zip`.

## Contents of the archive

Under `Saturn_Wallet/build/`:

- `index.html`, `index2.html` — extension pages
- `popup/` — the toolbar popup
- `background.js` — the extension background script
- `dist/`, `bootstrap/` — bundled application and vendor assets
- `favicon.ico`, `logo512.png`, `jupiter.png`, `original.png` — icons and images

This is compiled output rather than editable source.

## Loading it in a browser

```bash
unzip Saturn_Wallet.zip
```

Then open `chrome://extensions`, turn on **Developer mode**, choose
**Load unpacked**, and select `Saturn_Wallet/build/`.

## Note

The archive holds a build, not source, and also carries macOS `.DS_Store` and
`__MACOSX` entries. The corresponding source lives in the other Saturn
repositories.
