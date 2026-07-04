# kids-family prompt pack

Model: gpt-image-2
Proof size: 1920 x 1407

## Prompt

Create an opaque stylized art layer for the Kids And Family Ashland visitor map. Bright family activity layer with controlled teal and yellow accents, playful but not cartoonish shapes, and clear child-friendly anchors. Use the supplied control map as a strict registration reference. Do not move streets, trails, parks, POI anchors, map bounds, north orientation, or topography. Do not invent water, waterways, creeks, rivers, ponds, lakes, drainage channels, blue linear features, or hydrology marks unless a verified hydrology control layer is supplied. Do not render final readable labels, street names, business names, callout numbers, or attribution text. Keep the result geographically restrained: visitor-guide quality, whimsical and textured, but not cartoonish. The generated image will be composited under vector labels, POI anchors, and animation paths.

## Controls

- Base: /maps/control/base-control.png
- Roads: /maps/control/roads-control.png
- Mask: /maps/control/kids-family-mask.png

## Preservation Rules

- street geometry is locked
- POI coordinates are locked
- theme masks are locked
- labels and icons remain vector-controlled
- transparent overlays are created with post-processing masks

## Forbidden Operations

- invent POIs
- move roads or trails
- invent waterways or hydrology
- create readable map labels
- change the canvas aspect ratio
- request transparent GPT Image 2 output
