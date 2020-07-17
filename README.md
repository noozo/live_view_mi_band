# live_view_mi_band
A Phoenix LiveView statistics viewer for Xiaomi Mi Band (but not restricted to) fitness band

Currently supports:
- TODO

Mandatory screenshot:

- TODO

Notes:
- It's not a full Phoenix app, but it should be easy to adapt to a new one.
- There are some helpers (like pagination, date formatting, etc) that are not part of this codebase.

Example routing:

```
    scope "/fitness", Fitness do
      live "/", IndexView
    end
```

MIT Licence.
