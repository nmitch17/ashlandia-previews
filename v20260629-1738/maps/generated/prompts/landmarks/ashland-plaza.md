# Downtown Plaza / Lithia Fountain landmark sprite prompt

Landmark ID: ashland-plaza
Tier: 1
Confidence: typology
Status: ready
Public composition eligible: yes

## Prompt

Create a single realistic miniature visitor-map landmark sprite for Downtown Plaza / Lithia Fountain. Style: restrained hand-painted gouache and fine ink, muted Ashland visitor-map palette, warm paper-compatible colors, realistic simplified proportions, not cartoonish. Subject: downtown plaza civic node and Lithia fountain cultural cue. Allowed visual cues: small fountain/plaza paving; trees; civic gathering cue. Forbidden visual cues: invented streets; large water feature; fake statues; readable plaques. Use a generic typology cue; do not imply exact architecture. Output intent: transparent sprite to be placed on a factual GIS map. No background scenery beyond a tiny grounding shadow. No readable text, no logos, no people, no vehicles, no mascots, no invented adjacent buildings, no roads, no water, no labels, no map pins. Accuracy constraints: use only the listed sourceable architectural or place cues. If unsure, simplify to a generic typology cue rather than inventing details.

## Source

- Primary: https://www.opb.org/article/2024/02/02/lithia-water-drinking-fountains-ashland-oregon-historic-fountain/
- Secondary: https://www.atlasobscura.com/places/lithia-water-fountain

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
