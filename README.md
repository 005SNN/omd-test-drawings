# Test drawings for DWG readers

Small drawings made on purpose in **AutoCAD LT 2027 for Mac** from 2026-11-20 to 25 (sittings 1 to 9, 11 and 12), each to hold one kind of thing a DWG reader must get right. Every coordinate was typed; nothing comes from a real job. Where a `.dxf` sits beside a `.dwg`, it is AutoCAD's own DXF of that drawing (ASCII, 16 decimal places), saved from the same session: a witness of what the DWG holds.

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
| `mzinsneg-2018.dwg`, `.dxf`; `mzinsneg-2013.dwg`, `.dxf` | 2018, 2013 | A block `IO` (a rectangle and one INSERT of the block `RL`, an L of two lines) whose inner INSERT was placed from below: scales 1, 1, −1 and the extrusion 0,0,−1. `IO` is placed once the plain way. |
| `thickline-2018.dwg`, `.dxf`; `thickline-2013.dwg`, `.dxf` | 2018, 2013 | LINEs with a thickness: four in the block `TL` (235.5), placed once at scale 1 and once at 2.8125, and two loose in model space (662.4). Seen from above they are plain lines. |
| `mzinsnegvp-2018.dwg`, `.dxf`; `mzinsnegvp-2013.dwg`, `.dxf` | 2018, 2013 | `mzinsneg`'s drawing (blocks `IV` and `RV`) seen through one sheet viewport at 1:2. |
| `mzarcps-2018.dwg`, `.dxf`; `mzarcps-2013.dwg`, `.dxf` | 2018, 2013 | A block `AP` (a rectangle, a visible attribute and two arcs drawn from below, extrusion 0,0,−1) placed once on the sheet's paper at scale 1.5 with the attribute's value `A1`. Model space is empty. |
| `mzarcvp-2018.dwg`, `.dxf`; `mzarcvp-2013.dwg`, `.dxf` | 2018, 2013 | A rectangle and four arcs drawn from below (extrusion 0,0,−1) in model space, two of them at a height of 5, seen through one sheet viewport at 1:2. |
| `mzarcmir-2018.dwg`, `.dxf`; `mzarcmir-2013.dwg`, `.dxf` | 2018, 2013 | Two arcs drawn from below at a height of 5 and an INSERT mirrored by an X scale of −1, seen through one sheet viewport at 1:2. |
| `attmode0-2018.dwg`, `.dxf`; `attmode0-2013.dwg`, `.dxf` | 2018, 2013 | A block with a visible attribute (SEEN) and an invisible one (SECRET), and a loose attribute definition (LOOSE), saved with ATTMODE 0: only the loose definition shows. |
| `attdef2-2018.dwg`, `.dxf`; `attdef2-2013.dwg`, `.dxf` | 2018, 2013 | Two loose attribute definitions in model space, one visible (SHOWN) and one invisible (VEILED), saved with ATTMODE 2: both show. |
| `mzinsrotvp-2018.dwg`, `.dxf`; `mzinsrotvp-2013.dwg`, `.dxf` | 2018, 2013 | Three INSERTs of one block `MR` (four lines, flat in the block's plane) placed from below directly in model space: extrusion 0,0,−1, scales 1, rotations 0, 90 and 180, seen through one sheet viewport at 1:4. No hatch. |
| `xrefsheet-2018.dwg`, `.dxf`; `xrefsheet-2013.dwg`, `.dxf` | 2018, 2013 | A host drawing that places two other files: `sheetbdr.dwg` attached as an external reference in model space and again on the sheet `Layout1`, and `sheetov.dwg` as an overlay on the sheet. Three INSERTs, unscaled and unturned; the two blocks are empty in the host (BLOCK `70` 36 and 44); the path is relative (`REFPATHTYPE` 1). |
| `sheetbdr.dwg`, `sheetov.dwg` | 2018 | The two files `xrefsheet` places, kept beside it; one same content, never opened again after they were made. |
| `mlanno-2018.dwg`, `.dxf`; `mlanno-2013.dwg`, `.dxf` | 2018, 2013 | Fifteen MULTILEADERs with no text, directly in model space, in the style `Annotative`, made at the annotation scale 1/4" = 1'-0" and then set not annotative: `293` 0 and the entity's own scale `45` 48. Two sheets look at them through one viewport each. |
| `mzinshatvp-2018.dwg`, `.dxf`; `mzinshatvp-2013.dwg`, `.dxf` | 2018, 2013 | Three INSERTs placed from below directly in model space (extrusion 0,0,−1, scale 100, rotations 0, 90 and 90) of two blocks that each hold a SOLID hatch: `ST` (four lines, its hatch's boundary a polyline path) and `EA` (an arc and four lines, its hatch's path with a bulge). A rectangle round them; one sheet viewport at 1:4. |
| `ldrdim-2018.dwg`, `.dxf`; `ldrdim-2013.dwg`, `.dxf` | 2018, 2013 | Four straight LEADERs to an MTEXT `NOTE`, sloping right and left, with the arrowhead on (`LONR`, `LONL`) and off (`LOFFR`, `LOFFL`); a LEADER whose annotation is an INSERT of the block `LB` (`LBLK`); a linear dimension whose text is turned 30° (`DIM53`). Each on its own layer, with a label. |
| `hatchell-2018.dwg`, `.dxf`; `hatchell-2013.dwg`, `.dxf` | 2018, 2013 | Two concentric ellipses turned 30° and eight radial lines; four SOLID hatches (`H1` to `H4`, each on its own layer) picked inside the bands between the ellipses, so each boundary holds two elliptical arcs. |
| `splper-2018.dwg`, `.dxf`; `splper-2013.dwg`, `.dxf` | 2018, 2013 | Four splines: `A` closed from control points (degree 3, periodic); `B` closed through fit points (chord knots, periodic); `C` and `D` from control points that end where they start, not periodic (`C` smooth there, `D` with a corner at 0,0). |

`SHA256SUMS` lists every file's sha256.
