# Form Design Patterns (Interaction-First) 📝✅

## Overview
Forms are where users complete tasks. Efficient form design minimizes user effort and prevents validation errors.

## Core Principles
- **Label Placement**: Place labels above the input field for maximum scanability.
- **Inline Validation**: Provide feedback (success/error) as soon as the user finishes typing.
- **Grouped Information**: Use fieldsets or visual grouping for long forms (e.g., "Personal Info" vs. "Payment Details").
- **Smart Defaults**: Pre-filling fields based on user history or logical defaults.

## Common Components
- **Select Menus**: For choosing from a list of options (e.g., "Country", "Currency").
- **Toggles & Switches**: For binary choices (e.g., "Enable Notifications").
- **Progressive Disclosure**: Only showing fields if they are relevant based on a previous choice.

## Implementation (Tailwind / Component Concept)
```html
<!-- Input with Inline Validation and Label -->
<div class="mb-6">
  <label for="email" class="block text-sm font-bold text-slate-700 mb-2">Email Address</label>
  <input type="email" id="email" class="w-full px-4 py-3 rounded-lg border border-slate-300 focus:border-blue-600 focus:ring-1 focus:ring-blue-600 outline-none transition-all placeholder:text-slate-400" placeholder="jake@example.com">
  <p class="text-xs text-slate-500 mt-2">We'll never share your email with third parties.</p>
</div>
```

## Best For
- Account Creation & Profile settings.
- E-commerce Checkouts.
- Product Configuration (sentientPerp strategy builder).
