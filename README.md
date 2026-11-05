# Photo compositing lighting guide

A practical checklist for adding a person to a group photo so the result looks like one real photograph, whether you do it by hand (Photoshop, GIMP, Photopea) or with an AI tool.

It covers the four things that give a composite away, in the order they are usually noticed:

1. **Camera height and focal length** — the person was shot from a different height or with a wider lens.
2. **Horizon line and scale** — their head sits at the wrong height for where they stand.
3. **Light direction, softness and color** — they are lit from the other side, or by different light.
4. **Eye-line** — they look somewhere the rest of the group does not.

Each section has a quick test you can do by looking at the two photos before you start, and a fix.

- [The checklist (one page)](CHECKLIST.md)
- [Camera height and focal length](docs/01-camera-and-lens.md)
- [Horizon line, scale and placement](docs/02-horizon-and-scale.md)
- [Light direction, shadows and color temperature](docs/03-light-and-shadow.md)
- [Eye-line and pose](docs/04-eye-line-and-pose.md)
- [Doing it by hand: layer-by-layer steps](docs/05-manual-steps.md)
- [Diagrams (SVG)](diagrams/)

## The one-minute version

| Check | Look at the group photo | Choose a photo of the person that… |
|---|---|---|
| Camera height | Eye level, from above or from below? | was taken from the same height |
| Distance / lens | Usually 2–4 m, normal or 2× lens | was taken by someone else from 2–3 m, not an arm's-length selfie |
| Horizon | Where do the eyes of standing people sit? | can be scaled so their eyes land on the same line |
| Light side | Which side of the faces is brighter? | is lit from the same side |
| Light quality | Hard sun or soft shade? | has the same softness |
| Color | Warm evening, cool shade, yellow bulbs? | has similar color, or can be corrected |
| Shadow | Which way do shadows fall on the ground? | — (you will paint or generate one the same way) |
| Framing | Head to toe or waist up? | shows at least as much of the body |
| Eye-line | Where is everyone looking? | faces the same way |

## Why this exists

These are the same checks used on [addpersontophoto.org](https://addpersontophoto.org), a browser tool that adds a missing person to a group, family or wedding photo. Its step-by-step guide, with a method comparison (AI tool, Photoshop Generative Fill, Canva, GIMP/Photopea, hiring a retoucher), is at [How to add a person to a photo](https://addpersontophoto.org/how-to-add-a-person-to-a-photo).

The checklist is tool-agnostic: an AI model gets much better input when photo 2 already matches the camera height, light side and framing of photo 1, and a manual composite needs exactly the same matching.

## License

Text and diagrams: [CC BY 4.0](LICENSE). Share and adapt with credit.
