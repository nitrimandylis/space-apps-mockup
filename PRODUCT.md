# Lunar Landing Site Navigator (mockup)

## What it is

A mockup for the 2026 NASA Space Apps Challenge "Lunar Landing Site Navigator" challenge. It shows mission planners, educators and the public where the Sun and Earth sit relative to the horizon at lunar south pole landing sites, so they can judge solar power and direct-to-Earth radio windows quickly.

- `index.html`: homepage with a 3D Moon limb, Sun and Earth.
- `navigator.html`: orbitable 3D Sun, Earth and Moon with site pins, sight lines, a 30-day power and comms strip, and a site comparison list.

## Where it is headed

Hackathon is 14-15 November 2026. Before then the toy model gets replaced with real data:

- LOLA horizon masks per candidate site instead of the sine-wave `terrain()`.
- SPICE ephemerides instead of the toy `bodies()`.
- A polar mosaic for the Moon texture so the south pole doesn't smear.
- Any datasets the official challenge Resources tab recommends.
