# Sovereign Dark (GHOST Tactical UI) 🌑🧪

## Overview
A custom, high-contrast, low-eyestrain style designed for deep work, security research, and C2 orchestration. It is a fusion of Glassmorphism and Neubrutalism.

## Key Characteristics
- **Deep Navy/Black**: Uses `#020617` (Slate 950) or pure Black (`#000000`).
- **Neon Accents**: Cyber Green (`#22C55E`), Crimson Red (`#EF4444`), and Slate/Cyan for data lines.
- **Glass/Neon Borders**: Uses extremely thin (1px) borders with subtle glow (`drop-shadow`).
- **Monospaced Fonts**: Fira Code or IBM Plex Mono for all telemetry.

## Implementation (Tailwind)
```html
<div class="bg-black/90 border border-green-500/20 shadow-[0_0_15px_rgba(34,197,94,0.1)] rounded p-4 font-mono">
  <span class="text-green-500">[SYSTEM_OK]</span> TRK-771_LOCKED
</div>
```

## Best For
- Security Dashboards (ONYX SOVEREIGN).
- Radar/Telemetry Interfaces (AERIS-PCL).
- CLI-inspired web apps.

## Pros & Cons
- **Pros**: Zero eyestrain for late-night work; high clarity for data.
- **Cons**: Can feel "intimidating" or "hostile" for non-technical users.
