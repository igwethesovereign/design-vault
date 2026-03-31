# UI Navigation Patterns (SaaS Hierarchy) 🧭🗺️

## Overview
Navigation is the backbone of any application. Effective navigation minimizes cognitive load and allows users to move between tasks fluidly.

## Core Patterns
- **Sidebar (The Power User Layout)**: Vertically oriented navigation with hierarchical levels (e.g., Atlassian, GitHub).
- **Top Bar (Consumer Layout)**: Simple horizontal navigation for 3-5 main sections (e.g., Stripe, Shopify).
- **Global Search (Command Palette)**: A `Cmd + K` or `Ctrl + K` interface for power users (similar to OpenClaw's tool flow).
- **Breadcrumbs**: Helping users understand their position in deep data hierarchies (e.g., Dashboards > Trading > Pairs > BTC/USDT).

## Common Components
- **Collapsible Menus**: Saving screen real estate when the user doesn't need to navigate.
- **Badge Indicators**: Showing unread notifications or status (e.g., "New", "Alert").
- **User Profile/Settings**: Consistently placed in the top-right or bottom-left corner.

## Implementation (Tailwind / Component Concept)
```html
<!-- Navigation Sidebar with Hierarchical Levels -->
<aside class="w-64 bg-slate-50 h-screen border-r border-slate-200 px-4 py-8 flex flex-col">
  <div class="space-y-1">
    <a href="#" class="flex items-center gap-3 px-3 py-2 bg-blue-50 text-blue-700 rounded-lg font-semibold">Dashboard</a>
    <a href="#" class="flex items-center gap-3 px-3 py-2 text-slate-600 hover:bg-slate-100 rounded-lg">Analytics</a>
  </div>
</aside>
```

## Best For
- Complex SaaS (SentientPerp).
- Documentation sites (OpenClaw Docs).
- Management tools.
