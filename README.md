# Brand Hub

One-page brand source-of-truth for small businesses. 21 sections, autosaves in-browser, exports to JSON or Markdown.

Free tool from [GetNifty](https://getnifty.xyz).

## Structure

- `index.html` - landing page
- `hub.html` - the tool itself (21-section worksheet, localStorage autosave)
- `netlify.toml` - Netlify config

## Local preview

Any static server works. From this folder:

```
python -m http.server 8080
# or
npx serve .
```

Then open http://localhost:8080

## Deploy

Auto-deploys on push to `main` via Netlify.
