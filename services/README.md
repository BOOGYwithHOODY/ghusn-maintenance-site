# Service card images

Photographs for the service cards on the homepage and `/services`.

Name each file after the service slug:

| File | Service | Present |
| --- | --- | --- |
| `coffee-equipment.jpg` | Specialty coffee equipment | yes |
| `refrigeration.jpg` | Refrigeration & freezer systems | yes |
| `ice-machines.jpg` | Ice machines | yes |
| `commercial-kitchen.jpg` | Commercial kitchen equipment | yes |
| `preventive-maintenance.jpg` | Preventive maintenance | yes |
| `emergency-support.jpg` | Emergency technical support | yes |

A service with no file falls back to a branded panel carrying its icon, so the
grid stays consistent and photographs can be added one at a time.

Guidance:
- Landscape, around 900px wide is plenty — the cards render near 420px.
- The frame is cropped to 16:10, so keep the subject away from the edges.
- Use only photography the business owns or has licensed.

Note: replacing a file without renaming it can keep serving the old image in
development, because Next caches optimized images by URL. Delete
`.next/dev/cache/images` after a swap.

## Provenance

Three of these came from Pexels, whose licence permits commercial use without
attribution. The sources are recorded anyway, so the licence can be re-checked
later without guesswork:

| File | Source |
| --- | --- |
| `refrigeration.jpg` | https://www.pexels.com/photo/a-worker-in-a-storage-room-5953713/ |
| `ice-machines.jpg` | https://www.pexels.com/photo/ice-cubes-in-close-up-photography-7630009/ |
| `preventive-maintenance.jpg` | https://www.pexels.com/photo/close-up-photo-of-a-man-checking-a-power-voltage-10871929/ |

`coffee-equipment.jpg`, `commercial-kitchen.jpg` and `emergency-support.jpg`
were supplied by the business and their licensing has not been verified here.
