# open-webui-visual-toolkit
Fork of V4 to ensure availability

# Visuals Toolkit V4

18 visualization methods with interactive Plotly embeds and pure ASCII fallback. Dark-mode native. Works with any model.

## Chart Types

- **Tables** — auto-column detection, comparison tables with best-value highlighting
- **Bar / Line / Scatter** — single or multi-series with Plotly interactivity
- **Pie / Donut** — percentage breakdown with optional center hole
- **Gauge** — indicator dial with red/yellow/green color bands
- **Gantt** — horizontal timeline bars on a date axis
- **Sankey** — weighted flow diagrams between nodes
- **Radar** — spider/polar charts with multi-series overlay
- **Waterfall** — incremental change bars with running totals
- **Funnel** — conversion stages with % of initial
- **Candlestick** — OHLC financial charts with green/red coloring
- **Heatmap** — 2D color-scaled grid
- **Metrics Grid** — KPI cards in a responsive layout
- **Timeline** — styled event sequence
- **Flowchart** — box-drawing or edge-based graphs
- **Tree** — nested dicts or parent/child edge lists
- **Dashboard** — combine metrics, charts, and tables in one view

## Features

- **Dual output** — interactive Plotly HTML (`mode: auto`) or plain ASCII/Markdown (`mode: text`)
- **Dark-mode native** — styled for dark UIs out of the box
- **LLM-proof inputs** — defensive JSON coercion handles stringified arrays, escaped quotes, and type mismatches
- Auto-resizing iframes with fullscreen toggle on every embed
- Configurable via **Valves** — toggle CDN, set row/column caps, adjust chart height
