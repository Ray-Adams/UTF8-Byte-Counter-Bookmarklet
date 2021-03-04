# UTF-8 Byte Counter Bookmarklet
A code-golf-oriented bookmarklet that functions as a UTF-8 string length &amp; byte counter.

## Installation
Copy and paste the code below into the URL section of a new bookmark.
```javascript
javascript:(s=>alert(`That's ${s.length} characters, totaling ${new Blob([s]).size} UTF-8 bytes`))(prompt`UTF-8 Byte Counter`)
```

## Usage
1. Click the bookmarklet on any webpage, and you will see a prompt with the title `UTF-8 Byte Counter`.
2. Enter your text or string into the prompt and press <kbd>enter</kbd> or click the "OK" button.
3. An alert will pop-up with the UTF-8 string length and byte count of the data you provided.

## Compatability
Browser | Supported
--------|------------
Chrome  |     ✓
Firefox |     ✓
Safari  |     ✓
