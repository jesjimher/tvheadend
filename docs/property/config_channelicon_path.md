: 

The following placeholders are available:

Placeholder | Function
:----------:| --------
**%C**      | The transliterated channel name in ASCII (safe characters, so `WDR Köln` will be `WDR Koln`). Spaces will be transliterated as is, so check that your filesystem can manage spaces in filenames.
**%c**      | The channel name (URL encoded ASCII)

Example: `file:///tmp/icons/%C.png` or `http://example.com/%c.png`
