# Test drawings for DWG readers

Small drawings made on purpose in **AutoCAD LT 2027 for Mac** on 2026-11-20 and 21 (six sittings), each to hold one kind of thing a DWG reader must get right. Every coordinate was typed; nothing comes from a real job. Where a `.dxf` sits beside a `.dwg`, it is AutoCAD's own DXF of that drawing (ASCII, 16 decimal places), saved from the same session: a witness of what the DWG holds.

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
| `attrib-2018.dwg`, `.dxf`; `attrib-2013.dwg`, `.dxf` | 2018, 2013 | A title block: a rectangle and two single-line attribute definitions in a block, inserted once (TITLE = HOUSE, SHEET = A-02). |
| `attconst-2018.dwg`, `.dxf`; `attconst-2013.dwg`, `.dxf` | 2018, 2013 | A block with one constant attribute definition (MARK = CONST), inserted once. |
| `leader-2018.dwg`, `.dxf`; `leader-2013.dwg`, `.dxf`; `leader-2004.dwg`, `.dxf` | 2018, 2013, 2004 | One LEADER of three vertices with its arrowhead on, associated with an MTEXT (NOTE 1), dimension style ISO-25. |
| `mleader-2018.dwg`, `.dxf`; `mleader-2013.dwg`, `.dxf` | 2018, 2013 | One MULTILEADER with MTEXT content (NOTE 2). |
| `mleader-none-2018.dwg`, `.dxf`; `mleader-none-2013.dwg`, `.dxf` | 2018, 2013 | One MULTILEADER with no content (content type None). |
| `table-2018.dwg`, `.dxf`; `table-2013.dwg`, `.dxf` | 2018, 2013 | One table of 2 columns and 4 rows (title, header, two data rows), cells A to G. |
| `dimang3-2018.dwg`, `.dxf`; `dimang3-2013.dwg`, `.dxf` | 2018, 2013 | One three-point angular dimension (53°). |
| `ucs-2018.dwg`, `.dxf`; `ucs-2013.dwg`, `.dxf` | 2018, 2013 | A named UCS (U-ROT30) saved in the UCS table, with the world UCS current. |
| `pagesetup-2018.dwg`, `.dxf`; `pagesetup-2013.dwg`, `.dxf` | 2018, 2013 | A named page setup (PS-A4, no printer, ISO A4) beside the model's own. |
| `polyline2d-2018.dwg`, `.dxf`; `polyline2d-2013.dwg`, `.dxf` | 2018, 2013 | One closed old-style 2D POLYLINE of three vertices (PLINETYPE 0), not a lightweight polyline. |
| `T0-2013.dwg`, `.dxf` | 2013 | `T0.dwg` saved as 2013. |
| `F2-2013.dwg`, `.dxf` | 2013 | `F2-2018.dwg` saved as 2013. |
| `attjust-2018.dwg`, `.dxf`; `attjust-2013.dwg`, `.dxf` | 2018, 2013 | Two attributes in a block, inserted once: ROOM = KITCHEN middle-centred at 90,25, NO = 101 right-aligned at 170,8. |
| `attml-2018.dwg`, `.dxf`; `attml-2013.dwg`, `.dxf` | 2018, 2013 | A multi-line attribute (NOTE = SEE / DETAIL 4) in a block, inserted once. |
| `attrot-2018.dwg`, `.dxf`; `attrot-2013.dwg`, `.dxf` | 2018, 2013 | A block with one attribute (TAG = DOOR 7) inserted at rotation 30°. |
| `attscale-2018.dwg`, `.dxf`; `attscale-2013.dwg`, `.dxf` | 2018, 2013 | A block with one attribute (TAG = WIDE 2) inserted with X scale 2, Y scale 1. |
| `ldrhook-2018.dwg`, `.dxf`; `ldrhook-2013.dwg`, `.dxf` | 2018, 2013 | One LEADER whose last segment slopes at 45°, with the hook line AutoCAD adds before its MTEXT (NOTE 3). |
| `pl2darc-2018.dwg`, `.dxf`; `pl2darc-2013.dwg`, `.dxf` | 2018, 2013 | One closed old-style 2D POLYLINE of four vertices, one of them a half-circle arc (bulge 1). |
| `mzarc-2018.dwg`, `.dxf`; `mzarc-2013.dwg`, `.dxf` | 2018, 2013 | A 270° arc drawn in a UCS looking from below (normal 0,0,−1). |
| `mzins-2018.dwg`, `.dxf`; `mzins-2013.dwg`, `.dxf` | 2018, 2013 | A block (a flag of one polyline) inserted in a UCS looking from below (normal 0,0,−1). |
| `lttext-2018.dwg`, `.dxf`; `lttext-2013.dwg`, `.dxf` | 2018, 2013 | One line in the linetype GAS_LINE, which carries the text GAS in its dashes. |
| `stylew-2018.dwg`, `.dxf`; `stylew-2013.dwg`, `.dxf` | 2018, 2013 | A text style of width 0.8 (Arial) and one MTEXT in it, inside a block with a frame. |
| `mzell-2018.dwg`, `.dxf`; `mzell-2013.dwg`, `.dxf` | 2018, 2013 | An elliptical arc drawn from below (normal 0,0,−1) inside a block with a fixed frame. |
| `mlscale-2018.dwg`, `.dxf`; `mlscale-2013.dwg`, `.dxf` | 2018, 2013 | One MULTILEADER (NOTE 5) drawn at MLEADERSCALE 48, with a frame, inside a block inserted once. |
| `mlarrow-2018.dwg`, `.dxf`; `mlarrow-2013.dwg`, `.dxf` | 2018, 2013 | One MULTILEADER (NOTE 6) whose own arrowhead size is 6 where its style's is 4. |
| `mzoffarc-2018.dwg`, `.dxf`; `mzoffarc-2013.dwg`, `.dxf` | 2018, 2013 | A 270° arc drawn from below (normal 0,0,−1) with its centre off both axes, inside a block with a fixed frame. |
| `vpoff-2018.dwg`, `.dxf`; `vpoff-2013.dwg`, `.dxf` | 2018, 2013 | A sheet with two viewports onto the same figure: a plain one (CONTROL) and one switched off (OFF). |
| `vptwist-2018.dwg`, `.dxf`; `vptwist-2013.dwg`, `.dxf` | 2018, 2013 | A sheet with a plain viewport and one whose view is turned 30° (TWIST 30). |
| `vpdir-2018.dwg`, `.dxf`; `vpdir-2013.dwg`, `.dxf` | 2018, 2013 | A sheet with a plain viewport and one that looks from the side, view direction 0,−1,1. |
| `vpclip-2018.dwg`, `.dxf`; `vpclip-2013.dwg`, `.dxf` | 2018, 2013 | A sheet with a plain viewport and one clipped to a five-cornered polyline (CLIP). |
| `vpfrz-2018.dwg`, `.dxf`; `vpfrz-2013.dwg`, `.dxf` | 2018, 2013 | A sheet with a plain viewport and one in which the layer V-FRZ (holding the circle) is frozen alone. |
| `vpover-2018.dwg`, `.dxf`; `vpover-2013.dwg`, `.dxf` | 2018, 2013 | A sheet with a plain viewport and three overlapping pairs: two that overlap in part; a small one made after the large one it lies in; a small one made before the large one laid around it. |
| `psltwo-2018.dwg`, `.dxf`; `psltwo-2013.dwg`, `.dxf` | 2018, 2013 | Two sheets, each with one viewport onto a dashed line and a continuous one: Layout1 at PSLTSCALE 1, Layout2 at PSLTSCALE 0. |
| `xrefhost-2018.dwg`, `.dxf`; `xrefhost-2013.dwg`, `.dxf` | 2018, 2013 | A line and a circle with two external references: `border.dwg` attached and `borderov.dwg` overlaid, each stored by the relative path `./border.dwg`, `./borderov.dwg`. |
| `border.dwg`, `borderov.dwg` | 2018 | The two drawings `xrefhost` refers to, the same bytes: a rectangle labelled BORDER. |
| `attmode1-2018.dwg`, `.dxf`; `attmode1-2013.dwg`, `.dxf` | 2018, 2013 | Two inserts of a block with a visible attribute (SEEN 1, SEEN 2) and an invisible one (SECRET 1, SECRET 2), at ATTMODE 1: the invisible ones are not drawn. |
| `attmode2-2018.dwg`, `.dxf`; `attmode2-2013.dwg`, `.dxf` | 2018, 2013 | `attmode1` at ATTMODE 2: every attribute is drawn. |
| `spluni-2018.dwg`, `.dxf`; `spluni-2013.dwg`, `.dxf` | 2018, 2013 | Two fit-point splines through the same five points, 80 apart: one with chord knots (CHORD), one with uniform knots (UNIFORM). |
| `splsqrt-2018.dwg`, `.dxf`; `splsqrt-2013.dwg`, `.dxf` | 2018, 2013 | As `spluni`, the second spline with square-root knots (SQUARE ROOT). |
| `pl2dfit-2018.dwg`, `.dxf`; `pl2dfit-2013.dwg`, `.dxf` | 2018, 2013 | Two old-style 2D POLYLINEs of four vertices: one plain, one curve-fitted (FIT). |
| `pl2dspl-2018.dwg`, `.dxf`; `pl2dspl-2013.dwg`, `.dxf` | 2018, 2013 | Three old-style 2D POLYLINEs of four vertices: one plain, one spline-fitted quadratic (SPLINETYPE 5), one cubic (SPLINETYPE 6). |
| `ldrspl-2018.dwg`, `.dxf`; `ldrspl-2013.dwg`, `.dxf` | 2018, 2013 | Two LEADERs, each with its MTEXT: one straight (STRAIGHT), one with a spline path (SPLINE). |
| `imgclip-2018.dwg`, `.dxf`; `imgclip-2013.dwg`, `.dxf` | 2018, 2013 | The picture `omd6.png` attached at scale 100 (100 by 50), clipped to a rectangle 60 by 30 (CLIP). |
| `imginv-2018.dwg`, `.dxf`; `imginv-2013.dwg`, `.dxf` | 2018, 2013 | `imgclip` and a second copy of the picture whose rectangular clip is inverted: only its rim is drawn (CLIP INVERTED). |
| `imgplain-2018.dwg`, `.dxf`; `imgplain-2013.dwg`, `.dxf` | 2018, 2013 | The picture `omd6.png` attached at scale 100, whole (IMAGE). |
| `omd6.png` | | The picture the three image drawings attach by the relative path `./omd6.png`: 80 by 40 pixels. |
| `wipeout2-2018.dwg`, `.dxf`; `wipeout2-2013.dwg`, `.dxf` | 2018, 2013 | A five-cornered WIPEOUT over two lines that show at both its sides. |
| `xclipblk-2018.dwg`, `.dxf`; `xclipblk-2013.dwg`, `.dxf` | 2018, 2013 | Two inserts of a block (a rectangle, its diagonal and a circle): the lower one whole (CONTROL), the upper one clipped to a rectangle by XCLIP. |
| `anno18-2018.dwg`, `.dxf` | 2018 | An annotative linear dimension and an annotative MTEXT (ANNO) at the annotation scale 1:2. |
| `annovp-2018.dwg`, `.dxf` | 2018 | `anno18` with an annotative hatch and an annotative block added, every annotative object at 1:2 and 1:5, and a sheet with two viewports at 1:2 and 1:5. |

`SHA256SUMS` lists every file's sha256.
