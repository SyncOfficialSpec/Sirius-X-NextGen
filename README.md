# Sirius X - NextGen

Sirius X, presented through the [Rayfield Gen 3 Concept](https://github.com/SyncOfficialSpec/Rayfield_Gen_3_Concept) UI.

The full, unmodified Sirius X runs underneath. A tiny bridge exposes its own feature
tables, and a Gen3 Rayfield front-end drives them, so every toggle and slider fires the
exact same code path Sirius uses internally. Nothing is reimplemented or faked.

## Load

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/SyncOfficialSpec/Sirius-X-NextGen/main/SiriusX-NextGen.lua"))()
```

## What's in the panel

- **Character** - Noclip, Flight, Infinite Jump, Walk in Air, Anti Void, Ghost / Spectate,
  Invisibility, ESP, Auto Find, Fling, Shaders, Night & Day, Global Audio, Refresh, Respawn,
  Click Teleport (all 16 Sirius character actions)
- **Tuning** - player speed, jump power, flight speed, field of view, gravity, screen blur,
  auto aim (all 7 Sirius sliders, with their real ranges)
- **Interface** - jump to the Home / Character / Scripts / Players / Music / Settings panels,
  Command Search, Panic, and a toggle to bring back Sirius X's original interface

Press **K** to hide/show the panel.

## Notes

This is an unofficial community project. It is not affiliated with or endorsed by Sirius.
Original Sirius / Rayfield: [docs.sirius.menu](https://docs.sirius.menu).
