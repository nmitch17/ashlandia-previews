# Ashland Railroad District landmark sprite prompt

Landmark ID: railroad-district
Tier: 2
Confidence: typology
Status: ready
Public composition eligible: yes

## Prompt

Create a single realistic miniature visitor-map landmark sprite for Ashland Railroad District. Style: restrained hand-painted gouache and fine ink, muted Ashland visitor-map palette, warm paper-compatible colors, realistic simplified proportions, not cartoonish. Subject: Railroad Addition Historic District and railroad-era park context. Allowed visual cues: small historic storefronts; rail-era marker; depot-era color palette. Forbidden visual cues: moving train; fake tracks across current streets; readable signs. Use a generic typology cue; do not imply exact architecture. Output intent: transparent sprite to be placed on a factual GIS map. No background scenery beyond a tiny grounding shadow. No readable text, no logos, no people, no vehicles, no mascots, no invented adjacent buildings, no roads, no water, no labels, no map pins. Accuracy constraints: use only the listed sourceable architectural or place cues. If unsure, simplify to a generic typology cue rather than inventing details.

## Source

- Primary: https://www.nps.gov/places/ashland-railroad-addition-historic-district.htm
- Secondary: https://ashlandoregon.gov/facilities/facility/details/Railroad-Park-18

## Controls

- Base: /maps/control/base-control.png
- Roads: /maps/control/roads-control.png
- Anchors: /maps/control/real-world-anchors-control.png

## QA Checklist

- Primary source URL reviewed for the visual cue.
- Sprite has transparent background and only a tiny grounding shadow.
- No readable text, logo, mascot, vehicle, crowd, road, or water appears in the sprite.
- Exact rows depict only source-backed cues; typology rows remain generic.
- Sprite still reads at the target proof display size.

## Forbidden Operations

- draw roads, streets, trails, bridges, or paths
- draw water, waterways, creek lines, ponds, lakes, or blue hydrology marks
- draw readable labels, business names, street names, logos, plaques, or signs
- copy a source photo composition
- invent adjacent buildings, crowds, vehicles, mascots, banners, or animals
- change the map canvas, orientation, or landmark anchor
