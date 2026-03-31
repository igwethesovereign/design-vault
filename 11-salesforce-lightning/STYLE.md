# Salesforce Lightning Design System (SLDS) ☁️⚡

## Overview
SLDS is the comprehensive design system used by the world's leading CRM. It is optimized for large-scale enterprise workflows, high-density data, and complex user permissions.

## Key Principles
- **Clarity**: High-contrast, clean lines, and legible typography for power users.
- **Efficiency**: Designed for users who spend hours in the tool daily.
- **Consistency**: Maintaining the same experience across thousands of screens.
- **Mobile-First (Salesforce Mobile)**: Every pattern is responsive by default.

## Common Patterns
- **Record Detail Headers**: Quickly showing high-level info about a customer or lead.
- **Compact Layouts**: Minimizing height to show more rows in a table.
- **Utility Bar**: A fixed bar at the bottom for quick access to history, notes, and search.
- **In-App Navigation**: Multi-tab interfaces for complex workflows.

## Implementation (Tailwind / Component Concept)
```html
<!-- SLDS-style Data List Item -->
<div class="border-b border-slate-200 p-4 hover:bg-slate-50 cursor-pointer">
  <div class="flex items-center gap-3">
    <div class="w-10 h-10 bg-blue-100 rounded flex items-center justify-center text-blue-600 font-bold">JS</div>
    <div>
      <h3 class="text-sm font-semibold text-blue-600 hover:underline">Jake Shields</h3>
      <p class="text-xs text-slate-500">Sovereign Intelligence</p>
    </div>
  </div>
</div>
```

## Best For
- Enterprise CRM and Lead Management.
- High-density database management.
- Complex workflows with many user roles.

## Official Docs
[Salesforce Lightning Design System](https://www.lightningdesignsystem.com/)
