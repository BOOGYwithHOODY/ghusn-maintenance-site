# Hero slider images

Drop the hero photographs here using these exact file names:

| File | Shows |
| --- | --- |
| `kitchen-wiring.jpg` | Technicians repairing kitchen equipment wiring |
| `gas-range-inspection.jpg` | Technician inspecting a gas range with a report |
| `espresso-service.jpg` | Technician servicing an espresso machine |
| `espresso-internals.jpg` | Espresso machine internals being serviced |

The list, including the Arabic and English alt text, lives in
`src/content/hero-slides.ts`. Add or remove entries there to change the slides.

Guidance:
- Landscape, at least 1920px wide. The hero crops to fill, so keep the subject
  away from the extreme edges.
- Use only photography the business owns or has licensed. Do not use
  watermarked stock previews — the watermark is visible to every visitor and
  the preview carries no licence to publish.

## Adding the images

1. Copy the four photographs into this folder using the names in the table.
2. Restart the dev server (`npm run dev`) — the manifest is read on the server,
   so a new file is picked up on the next build.

To change how many slides there are, edit `src/content/hero-slides.ts`. A slide
whose file is absent is skipped; with none present the hero keeps its gradient.
