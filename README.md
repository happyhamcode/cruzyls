# Cruzyls

A pirate-themed prep guide for a first Royal Caribbean cruise. One static page with tabbed sections covering everything to sort out before boarding.

Live at https://cruiselist.happyham.co (currently on hold).

## What's in it

- **Fill yer sea chest**: what to pack
- **Ship's manifest & papers**: documents to bring
- **Contraband & what stays ashore**: items that are banned or limited
- **Grog, bubbly & bites**: drinks and food rules
- **Setting sail**: how boarding day unfolds

## Run it

No build step and no dependencies. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

`index.html` and `cruise-prep-guide.html` are the same page; `index.html` is the one that gets served.

## Notes

- Fonts load from Google Fonts (Luckiest Guy, Baloo 2, Nunito). The page needs a network connection for them and falls back to system fonts without one.
- The packing and policy details reflect Royal Caribbean's rules at the time they were written. Check the cruise line's current policies before you sail.
