# Keyboard Controls

Larvaworld's visualization window supports interactive keyboard and mouse controls for real-time exploration.

---

## Quick Reference

| **Overlay**         |      | **Drawing**      |     | **Color**         |     | **Environment** |     | **Inspect**    |     | **Simulation**   |       |
| ------------------- | ---- | ---------------- | --- | ----------------- | --- | --------------- | --- | -------------- | --- | ---------------- | ----- |
| State (status text) | s    | Midline          | m   | Random colors     | r   | Odor aura       | u   | Focus / follow | f   | Snapshot         | i     |
| Clock (time)        | t    | Contour          | c   | Color by behavior | b   | Windscape       | w   |                |     | Pause            | space |
| Scale bar           | n    | Head             | h   | Black background  | g   | Plot odorscapes | o   |                |     |                  |       |
| IDs                 | TAB  | Centroid         | e   |                   |     | Odorscape 0–9   | 0-9 |                |     | Larva collisions | y     |
| Camera pan          | ↑↓←→ | Trails           | p   |                   |     |                 |     |                |     |                  |       |
| Trail duration      | +/-  | Trail color mode | x   |                   |     |                 |     |                |     |                  |       |
| Sensors             | j    | Orientations     | k   |                   |     |                 |     |                |     |                  |       |
| Segments            | l    |                  |     |                   |     |                 |     |                |     |                  |       |

**Legend**:

- `L*` = Left mouse button
- `R*` = Right mouse button
- `M*` = Mouse scroll wheel

---

## Screen Controls

| Key      | Action     | Description                              |
| -------- | ---------- | ---------------------------------------- |
| **s**    | State text | Toggle status overlay (simulation state) |
| **t**    | Clock      | Show/hide simulation clock               |
| **TAB**  | IDs        | Show/hide larva IDs                      |
| **n**    | Scale bar  | Toggle scale bar                         |
| **↑↓←→** | Pan        | Move viewport                            |
| **M\***  | Zoom       | Scroll to zoom in/out                    |

---

## Drawing Controls

| Key     | Action         | Description                |
| ------- | -------------- | -------------------------- |
| **m**   | Midline        | Toggle 12-point midline    |
| **c**   | Contour        | Toggle body contour        |
| **h**   | Head           | Highlight head segment     |
| **e**   | Centroid       | Show body centroid         |
| **p**   | Trail          | Toggle trajectory trails   |
| **+/-** | Trail duration | Adjust trail length        |
| **x**   | Trail color    | Cycle trail color modes    |
| **j**   | Sensors        | Toggle sensor rendering    |
| **k**   | Orientations   | Toggle orientation vectors |
| **l**   | Segments       | Toggle body segments       |

---

## Color Modes

| Key   | Action     | Description                              |
| ----- | ---------- | ---------------------------------------- |
| **r** | Random     | Random colors per larva                  |
| **b** | Behavior   | Color by behavior state (run/pause/turn) |
| **g** | Background | Toggle black background                  |

---

## Environment / Landscapes

| Key     | Action          | Description                                                |
| ------- | --------------- | ---------------------------------------------------------- |
| **u**   | Odor aura       | Toggle odor aura around odor sources                       |
| **w**   | Windscape       | Toggle windscape rendering (if the environment has wind)   |
| **o**   | Plot odorscapes | Export odorscape plot (uses the current odor layers)       |
| **0-9** | Odorscape N     | Toggle visibility of odorscape layer by index (if present) |

---

## Simulation Control

| Key       | Action     | Description                 |
| --------- | ---------- | --------------------------- |
| **space** | Pause      | Pause/resume simulation     |
| **i**     | Snapshot   | Save current frame as image |
| **y**     | Collisions | Toggle larva overlap mode   |

---

## Mouse Actions

| Input   | Action      | Notes                           |
| ------- | ----------- | ------------------------------- |
| **L\*** | Select item | Ctrl+click toggles multi-select |
| **M\*** | Zoom        | Scroll wheel                    |

## Usage Examples

### Following a Larva

1. **Left-click** on a larva to select it
2. Press **f** to lock camera
3. Press **m** to show midline
4. Press **p** to show trail

### Creating a Video

1. Run experiment with `screen_kws={'vis_mode': 'video', 'save_video': True, 'video_file': 'my_video'}`
2. Adjust drawing options (**m**, **c**, **p**)
3. Select color mode (**r** or **b**)
4. Simulation auto-exports to MP4

### Inspecting Behavior

1. **Left-click** on a larva to select it
2. Press **f** to follow the selected larva

---

## Related Documentation

- {doc}`visualization_snapshots` - Visualization examples
- {doc}`web_applications` - Web-based dashboards
- {doc}`../working_with_larvaworld/replay` - Replay mode
