# Lithia Park landmark sprite prompt

Landmark ID: lithia-park
Tier: 1
Confidence: exact
Status: ready
Public composition eligible: yes

## Prompt

Create a single realistic miniature visitor-map landmark sprite for Lithia Park. Style: restrained hand-painted gouache and fine ink, muted Ashland visitor-map palette, warm paper-compatible colors, realistic simplified proportions, not cartoonish. Subject: Lithia Park as downtown crown-jewel park with formal greens, Japanese garden, duck ponds, sycamores, bandshell/fountain context. Allowed visual cues: grove; formal garden entry; park path; bandshell silhouette if space allows. Forbidden visual cues: invented creek lines; fake ponds; fantasy forest; animals. Exact depiction is allowed only for the listed source-backed visual cue. Output intent: transparent sprite to be placed on a factual GIS map. No background scenery beyond a tiny grounding shadow. No readable text, no logos, no people, no vehicles, no mascots, no invented adjacent buildings, no roads, no water, no labels, no map pins. Accuracy constraints: use only the listed sourceable architectural or place cues. If unsure, simplify to a generic typology cue rather than inventing details.

## Source

- Primary: https://ashlandoregon.gov/facilities/facility/details/Lithia-Park-22
- Secondary: https://www.nps.gov/places/lithia-park.htm

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
