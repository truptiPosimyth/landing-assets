# landing-assets

Public, hotlinkable assets for the POSIMYTH animated landing-page master prompts.
These files are meant to be referenced directly by URL so the prompts are self-contained.

## Astra Interiors — `astra/`
Interior photography + brand logotype, favicon and grain texture.
Serve via jsDelivr CDN, e.g.:

```
https://cdn.jsdelivr.net/gh/truptiPosimyth/landing-assets@v1/astra/interior-1.jpg
```

## NOX drone — `nox/`
`model.glb` — the 3D LiDAR-drone (~28 MB). Loaded at runtime by Three.js (GLTFLoader),
so it needs correct CORS. Served from raw.githubusercontent.com (CORS-safe, 100 MB limit):

```
https://raw.githubusercontent.com/truptiPosimyth/landing-assets/v1/nox/model.glb
```

Tag `v1` gives stable, cacheable URLs. Bump the tag to publish new versions.
