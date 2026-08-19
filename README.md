# Spanish StoryMap — Manuel Fernández

Interactive [StoryMapJS](https://storymap.knightlab.com/) project (written in elementary Spanish) that follows one 18th-century case from **primary source** to **structured data** to **mapped narrative**.

This is a digital-history communication piece: the code is HTML + JSON; the work is research design and storytelling.

## Live map

Open [`index.html`](index.html) in a browser, or use GitHub Pages if it is enabled on this repo.

## What the story covers

1. **La transcripción digital** — turning a historical document into usable text  
2. **Organizar los datos** — structuring people, places, and events  
3. **Contar la historia con StoryMapJS** — walking a reader through locations on a map  

## Files

| File | Role |
| --- | --- |
| `index.html` | StoryMap viewer |
| `published.json` | Published slide / location data |
| `draft.json` | Working draft of the same data |
| `_images/` | Images used in the map |
| `draft.html` | Draft viewer |

## How to view locally

```bash
git clone https://github.com/vivic0107/Spanish-storyMap.git
open index.html
```

No build step. If slides do not load from `file://`, serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Skills this demonstrates

Research communication · narrative structure · JSON content modeling · bilingual (Spanish) writing · Knight Lab StoryMap
