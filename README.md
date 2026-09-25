# WillThisWork Site

This project is a browser-based chat room app built as a lightweight static site. It keeps the current functionality in a single-page interface and adds a simple local hosting setup so it can be run as a stable site.

## Run locally

From the project root:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Scripts

```bash
npm start
```

This uses Python's built-in static file server so the site can be served without any extra install steps.

## Notes

- The app uses ntfy.sh for room messaging and presence.
- It is designed to be served as a static site and is suitable for local hosting or deployment to a static host.
