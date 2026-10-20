# terminal.oddsengine.live

The OddsEngine crypto terminal. One page, no build step.

- `index.html` is the whole site. The API address sits at the top.
- Reads `GET /v1/crypto` from the platform. While the `crypto` switch is off,
  visitors see the coming soon page. With `?admin=YOUR_ADMIN_KEY` once in the
  address bar, this browser sees the full terminal as a preview.
