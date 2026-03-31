# Material Design 3 (Android Standard) 📱⚡

## Overview
Google's latest evolution of Material Design, focusing on "Material You" personalization, adaptive layouts, and expressive motion. It is the industry standard for Android and multi-platform Google services.

## Key Principles
- **Personalization (Dynamic Color)**: UI colors are derived from the user's wallpaper/preferences using the M3 color system.
- **Expressive Motion**: Transitions that are physically-based and responsive to user input.
- **Adaptive Layouts**: Built for everything from phones to foldable screens and desktops.
- **State Layers**: Using overlays to indicate interaction states (hover, focus, pressed).

## Common Patterns
- **Floating Action Button (FAB)**: The primary action on a screen, often placed at the bottom right.
- **Navigation Rail**: A vertical navigation bar for tablets and desktops.
- **Cards and Sheets**: Used to group content and provide contextual actions.

## Implementation (Tailwind / Component Concept)
```html
<!-- M3-inspired Card -->
<div class="bg-surface-variant text-on-surface-variant rounded-3xl p-6 shadow-sm hover:shadow-md transition-shadow">
  <h2 class="text-xl font-medium">Feature Title</h2>
  <p class="mt-2">M3 emphasizes accessibility and clear visual hierarchy.</p>
</div>
```

## Best For
- Android applications.
- High-accessibility web apps.
- Enterprise applications requiring a systematic approach.

## Official Docs
[Material.io](https://m3.material.io/)
