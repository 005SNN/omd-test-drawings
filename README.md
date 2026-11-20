# Test drawings for DWG readers

Small drawings made on purpose in **AutoCAD LT 2027 for Mac** on 2026-11-20 (two sittings), each to hold one kind of thing a DWG reader must get right. Every coordinate was typed; nothing comes from a real job. Where a `.dxf` sits beside a `.dwg`, it is AutoCAD's own DXF of that drawing (ASCII, 16 decimal places), saved from the same session: a witness of what the DWG holds.

Released into the public domain under **CC0 1.0** (`LICENSE`): use them for anything, no attribution needed.

| Files | Version | What they hold |
|---|---|---|
| `omd-plan-2018.dwg`, `.dxf`; `omd-plan-2013.dwg` | 2018, 2013 | A small floor plan in millimetres (INSUNITS 4): layers, eight dimensions (linear, aligned, radius, diameter, angular, ordinate) with ISO-25 at DIMSCALE 50, DIMASSOC objects; an ISO A3 layout with two viewports at 1:50 and 1:20. |
| `anno-2018.dwg`, `.dxf` | 2018 | Annotative MTEXT and dimension at 1:50 and 1:100, each scale with its own position (context data). |
| `F1-2018.dwg`, `.dxf`; `F1-2013.dwg`; `F2-2018.dwg`, `.dxf` | 2018, 2013 | Dashed lines with the annotation scale 1:50; F1 with MSLTSCALE 1, F2 with MSLTSCALE 0. |
| `G1-2018.dwg`, `.dxf`; `G1-2013.dwg`; `G2-2018.dwg`; `G2-2013.dwg` | 2018, 2013 | Dashed lines at LTSCALE 50, one with its own linetype scale 0.5, and a layout viewport at 1:50; G1 with PSLTSCALE 1 (the lines look solid on the sheet), G2 with PSLTSCALE 0 (dashed). |
| `fields-2018.dwg`, `.dxf`; `fields-2013.dwg` | 2018, 2013 | Four fields: date, file name, an object's area, and a sheet number in an attribute definition. |
| `gradient-2018.dwg`, `.dxf` | 2018 | Two gradient hatches: index colours 1 and 5; a colour-book colour and 5. |
| `T0.dwg`, `T0.pdf` | 2018 | Hatches, a wipeout and a solid, and AutoCAD's own PDF plot of it. |
| `normals-2018.dwg`, `.dxf`; `normals-2013.dwg` | 2018, 2013 | An arc, a bulged polyline, an elliptical arc, a text, a block with an attribute, a linear dimension and a far circle, each mirrored about x = 20000 (MIRRTEXT 0: only the ellipse is stored under a −Z normal); a circle, text and block drawn in a UCS turned 30° about X at elevation 500; a fit-point spline out of the XY plane. |
| `H1-2018.dwg`, `.dxf`; `H1-2013.dwg` | 2018, 2013 | A text style of width 0.8 and oblique 15° (Arial) and one MTEXT in it. |
| `gradient2-2018.dwg`, `.dxf` | 2018 | A gradient hatch with a colour-book colour, changed to a SOLID fill (AutoCAD keeps the gradient's colour records). |

`SHA256SUMS` lists every file's sha256.
