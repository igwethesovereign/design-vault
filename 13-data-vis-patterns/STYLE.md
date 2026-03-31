# Data Visualization UI Patterns (Insight-First) 📊🔍

## Overview
Data visualization transforms raw numbers into actionable insights. It's about finding the right balance between detail and clarity.

## Core Patterns
- **Trend Charts (Sparklines)**: Small, simple charts to show historical changes at a glance (e.g., TradingView).
- **Distribution Charts (Bar/Pie)**: Showing composition and comparative performance (e.g., Portfolio Allocation).
- **Correlation Charts (Scatter)**: Finding relationships between data points (e.g., Risk vs. Return).
- **Interactive Legends**: Clicking on a legend item to hide/show data series on the chart.

## Common Components
- **Tooltip Popups**: Showing the exact data point value on hover.
- **Range Selectors**: Allowing users to zoom in on specific time periods (1H, 1D, 1W, 1M).
- **Threshold Lines**: Visual markers for key levels (e.g., "Profit Target", "Stop Loss").

## Implementation (Tailwind / Component Concept)
```html
<!-- Data Vis Card with Sparkline Placeholder -->
<div class="bg-white rounded-xl border p-4 shadow-sm">
  <div class="flex justify-between items-baseline mb-4">
    <h4 class="text-sm font-bold text-slate-500 uppercase tracking-wider">Trading Volume</h4>
    <span class="text-xs text-green-600 font-bold">+2.4%</span>
  </div>
  <div class="h-16 w-full bg-slate-50 rounded flex items-center justify-center text-xs text-slate-400">
    [SPARKLINE_CHART_PLACEHOLDER]
  </div>
</div>
```

## Best For
- FinTech (sentientPerp).
- Performance Analytics (PolHunter).
- Scientific/Engineering tools.
