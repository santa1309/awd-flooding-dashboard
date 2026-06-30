# AWD & Flooding Plot Dashboard — Kharif 2025

Interactive, fully self-contained dashboard for paddy AWD / flooding analysis in
**Nalgonda, Telangana (Kharif 2025)** — 5,085 plots, Sentinel-1 SAR + IMD rainfall.

Open **`index.html`** in any browser (works offline; no server or internet needed).
If GitHub Pages is enabled, it is viewable directly at the Pages URL.

## Features
- Color the plots by any variable (Total Flood Days, Wet/Dry Days, Flooding due to
  Rain, **Paddy Area (ha)**, Transplanting Flooding, Season Days, AWD Cycles,
  Sowing type, Crop method DSR/TPR).
- **Search a plot by ID** — zooms, highlights, and opens its details.
- Click any plot to see its metrics plus a **relative water-depth** chart
  (RWDI × 15 cm) across the season.

## Notes
- Relative water depth is *relative* (RWDI × 15 cm), not absolute depth.
- "Flooding due to Rain" = flooded days coinciding with IMD rainfall (≥10 mm over
  the prior 3 days), counted after establishment — attribution, not proof.
