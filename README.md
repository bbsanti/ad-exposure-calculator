# Ad Exposure Calculator

**Use it:** https://bbsanti.github.io/ad-exposure-calculator/

Measure how much of the screen an ad takes up. Load a broadcast screenshot, draw a box (or a polygon for
angled signage) around each ad, and the tool reports the exact pixel count and share of screen for every
shape, every sponsor and all ads combined.

Everything runs in your browser. Screenshots are never uploaded anywhere.

## Using it

1. **Open screenshots**, drag them onto the page, or paste one with Ctrl+V. Several at once is fine.
2. Pick or add a sponsor in the right-hand panel.
3. Drag a **Box** (B) around the ad. For a floor logo or other angled ad, use **Polygon** (P) and click
   around it; press Enter or click the first point to close.
4. If the screenshot includes player controls or desktop, use **Frame** (F) to mark just the video picture.
   Shares are then measured against that area only.
5. **Copy table** pastes into Sheets or Excel, one row per sponsor per screenshot plus an all-ads total.
   **Download CSV** and **Annotated PNG** save files.

## How pixels are counted

A pixel counts when its centre lies inside the shape, so a box with whole-pixel edges covers exactly
width × height pixels. Sponsor and all-ads totals are unions: where shapes overlap, the shared pixels are
counted once. *Count pixels at* rescales the counts to 1920 × 1080, 3840 × 2160 or 1280 × 720 when the
screenshot was captured at a different size; the percentages do not change.

## Keys

| Key | Action |
|---|---|
| B / P / V / F | Box, Polygon, Move, Frame |
| Alt + drag | New box on top of the selected one |
| Del | Delete the selected shape |
| Arrows | Nudge 1 px (Shift: 10 px) |
| Ctrl + Z / Ctrl + Shift + Z | Undo / redo |
| Space + drag, wheel, 0, 1 | Pan, zoom, fit, 100% |
| T | Show or hide tags |
