# IBM Carbon Design System (Enterprise Scaling) 💼🏢

## Overview
IBM's open-source design system for products and digital experiences. It is an industry leader in enterprise-grade accessibility, scalability, and technical clarity.

## Key Principles
- **2:1 Ratio**: Information density is balanced for clarity.
- **Data Visualization**: A robust set of patterns for charts, tables, and complex data sets.
- **Grids and Spacing**: Uses a 2x spacing scale (4px, 8px, 16px, etc.) for absolute consistency.
- **High-Contrast Themes**: Accessible by default, including high-contrast and white themes.

## Common Patterns
- **Data Tables**: Powerful, sortable, and filterable.
- **Side Panels**: Contextual information that doesn't block the main view.
- **Status Indicators**: Uses specific, accessible colors for info, success, warning, and danger.

## Implementation (Tailwind / Component Concept)
```html
<!-- Carbon-style Data Table Header -->
<div class="bg-slate-100 border-b border-slate-300 px-4 py-3 text-sm font-semibold flex items-center justify-between">
  <span>System Logs</span>
  <button class="bg-blue-600 hover:bg-blue-700 text-white px-3 py-1 text-xs">EXPORT CSV</button>
</div>
```

## Best For
- Enterprise SaaS platforms (SentientPerp backend, AERIS-PCL Admin).
- Internal Tools and Dashboards.
- Complex Data-Rich Applications.

## Official Docs
[IBM Carbon Design System](https://carbondesignsystem.com/)
