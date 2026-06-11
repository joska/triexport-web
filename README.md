# triexport-web

Static site for the TriExport iOS app — landing page, support contact, and privacy policy.

Lives at https://triexport.sekava.dev.

## Layout

- `index.html` — landing / support page (Tailwind via Play CDN)
- `img/` — app icon, screenshots, App Store badges
- `files/` — externally linked legal docs (privacy policy)

## Local preview

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000/>.
