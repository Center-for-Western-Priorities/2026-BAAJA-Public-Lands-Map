# BAAJA public lands map

Interactive scrolling map from the Center for Western Priorities and Earthworks showing 16 public landscapes the Bipartisan American Affordability and Jobs Act (BAAJA) could put at risk.

## Files

- `index.html`: the whole page. Map data, site text, and code are inline.
- `images/`: one photo per site plus `hero.jpg`. Credits and licenses appear in each caption on the page.
- `.nojekyll`: tells GitHub Pages to serve the files as is.

## Hosting

GitHub Pages: Settings > Pages > Deploy from a branch > `main`, folder `/ (root)`.

## Links to a specific place

Add a place ID to the end of the URL to open the map scrolled to that place, for example `#chaco`.

IDs: `chaco`, `taylor`, `chama`, `bwca`, `anwr`, `bears`, `gsenm`, `oak`, `ambler`, `teshekpuk`, `tongass`, `otero`, `beehive`, `townsite`, `roan`, `kennedy`.

## Embedding on westernpriorities.org

Use a full-width page template and one iframe sized to the screen:

```html
<iframe src="https://center-for-western-priorities.github.io/2026-BAAJA-Public-Lands-Map/" title="BAAJA public lands map" style="width:100%;height:100vh;border:0;display:block"></iframe>
```
