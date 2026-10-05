# Slide Label Printer · طابعة ملصقات الشرائح

Browser-based label printer for histopathology slides, using A4 sticker sheets and an ordinary office laser printer. Works on PC and phone, no installation, no server. All data stays in the browser (localStorage).

## Features
- Label per slide: lab name, patient name, case number (`2368-26`, year auto), cassette (`A1`), level (`L2`), stain, date
- Cassette syntax: `A1-A3, B1-2, C` · `A-F` · `A1-D2`
- Multiple levels and stains per case (H&E, PAS, ZN, IHC…)
- Number ranges (e.g. 5000 → 5100) with optional patient names pasted in order
- Bulk paste from Excel: `Name ; Number ; Cassettes ; Levels ; Stain`
- Start from any label on a partially used sheet
- Calibration page and X/Y offsets in mm
- Label size presets (22×22, 25×20, 24×19, 22×18) or custom

## Printing
In the print dialog: **Actual size / 100%**, margins **None**, headers & footers **off**.

## Deploy
Static site. Enable GitHub Pages → Deploy from branch → `main` / root.
