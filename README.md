# ARCANADE

*one mage against the siege* — a Contra-style run-and-gun in full silhouette,
where the spells are the only light.

**Slice I — the fire mage.** Storm the Wall of Vhal: field, burning bridge,
siege camp, wall breach, and the Siege Wyrm.

## The rules that matter

- **Ward + 1**: one ward absorbs one hit; the next kills. Relics restore the ward.
- **Relics swap your whole attack** (Contra weapon capsules): Ember Fan,
  Flame Lance, Greatfire, Drake's Breath.
- **Fire spreads.** Grass, bridges, barricades, tents, catapults and hoardings
  all catch, chain, and burn away — including the planks you're standing on.
- **Dying resets the setpiece** you died in (gate hordes, the boss).

## Controls

WASD move · mouse aim · click cast · SHIFT (or right-click) dash · S drop · ESC pause

## Dev

```
python serve.py 5818
```

Single-file Canvas 2D, no dependencies. `window.ARCANADE` exposes a debug API
(`warp`, `ignite`, `god`, `state`, entity lists) for scripted playtests.
- "Echoes of Time" — Kevin MacLeod (incompetech.com), CC BY 4.0 — Level III
