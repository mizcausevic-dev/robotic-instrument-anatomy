# Robotic surgical instrument, mechanical anatomy

A 34-second, 1,020-frame cutaway of a generic tendon-driven wristed instrument. The clock is the frame index. Hardware stays muted metal. Cyan, gold, and violet are diagram colors, not glowing parts.

Open `index.html`. Space plays and pauses. The stage ticks jump to frames 0, 150, 300, 510, and 750. The last frame holds.

`index.html` and `README.md` keep the names GitHub Pages and GitHub expect. The brief also locks the stage colors, so this film does not carry a theme picker.

## What the film shows

| Frames | Time | What changes |
| --- | --- | --- |
| 0–149 | 0–5s | Proximal housing, four actuation inputs, shaft |
| 150–299 | 5–10s | Longitudinal section and schematic tendon routes |
| 300–509 | 10–17s | Wrist pitch, yaw, and jaw, in slow motion |
| 510–749 | 17–25s | Proximal sensing and an optional insulated energy path |
| 750–1019 | 25–34s | Pull back to a generic arm, then hold |

Scale changes, slow motion, and time compression are labeled on screen. Sections remove a near wall. They do not explode the instrument.

## What it refuses to invent

- Cable diameters, pulley ratios, and cable counts as measurements. The pairs are a schematic for pitch, yaw, and jaw.
- Distal encoders and force feedback. Sensing in this model is proximal. Joint position is inferred from drive motion.
- Shaft roll is a fourth input and is not animated, so the section plane stays put.
- Clinical setup, energy settings, or steps for use on a patient.
- A named surgical system. The arm's joint layout is illustrative. The rings at the cannula are a remote-center diagram, not a measured linkage.

Review status: working explainer, not a certified engineering or medical reference. Check subject-specific details before publication.

## Run

Any static server, or open the file directly. Query `?frame=400` opens that frame paused. `?frame=0&play=1` plays from the start. Reduced motion does not autoplay.

No build step. No dependencies. No analytics tag. No form.

There is no lead form. Collecting contact data would need a stated purpose, a disclosure, a retention rule, and an owner. This page's job is the mechanism.

## GitHub

About: Frame-driven mechanical anatomy of a generic tendon-driven robotic surgical instrument.

Topics: `medical-technology` `surgical-robotics` `explainer` `webgl` `mechanical-anatomy` `tendon-driven` `visualization` `education` `robotics` `anatomy`

Pages: serve this directory. The live branch is `gh-pages`.
