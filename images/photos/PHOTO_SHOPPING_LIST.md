# Photo shopping list — Groundwyre site

The site's HTML is already wired to display real photos from this folder. Right now
each spot shows a placeholder (a striped box with the expected filename) because
the actual image files aren't here yet — the sandbox that built this site can't
download binary files from Unsplash/Pexels/etc. (network is restricted to a small
allowlist), so this last step needs a human with a browser.

**How to fill each one in:** open the link, click the free "Download" button on
Unsplash (no account needed), rename the file to exactly the filename listed, and
drop it into this folder (`groundwyre-site/images/photos/`). Refresh the page and
the placeholder becomes the photo automatically — no code changes needed.

All links below are Unsplash photos, free to use under the Unsplash License
(no attribution legally required, though crediting the photographer is a nice
practice if you ever take this beyond a demo).

| Filename | Used on | Unsplash link |
|---|---|---|
| `aerial-highway.jpg` | Homepage — photography strip | https://unsplash.com/photos/an-aerial-view-of-a-highway-and-a-bridge-Hpw3kjS7BMM |
| `paving-crew.jpg` | Homepage — photography strip | https://unsplash.com/photos/workers-paving-a-road-with-asphalt-and-asphalt-machine-SwU1fGx__Gk |
| `construction-equipment.jpg` | Homepage strip + Solutions (Public Works) | https://unsplash.com/photos/road-construction-equipment-lined-up-on-wet-asphalt-d2KkAn2opOs |
| `highway-interchange-dusk.jpg` | Solutions (Transportation Planner) | https://unsplash.com/photos/aerial-view-of-a-busy-highway-interchange-at-dusk-zzM7voOp6Tk |
| `hardhat-crew.jpg` | Company — Leadership section | https://unsplash.com/photos/construction-workers-in-hard-hats-and-vests-huddle-together-nlXv_JCfSHc |
| `main-street.jpg` | Company — story banner | https://unsplash.com/photos/a-quiet-street-in-a-small-town-nsJMV5dIRXY |
| `water-infrastructure.jpg` | Product — Asset Registry module | Pick any photo from https://unsplash.com/s/photos/water-infrastructure (no single best pick — choose one with visible pipes or a treatment facility) |
| `council-meeting.jpg` | Product — Council & Public Reporting module | Pick any photo from https://unsplash.com/s/photos/public-meeting or https://unsplash.com/s/photos/government-meeting (look for people seated at a dais or table, documentary style — avoid stock-y handshake photos per the brand's Visual Direction guidelines) |

## Why two of these are "pick one" instead of a direct link

Unsplash's search-result pages are rendered with JavaScript, so a plain web search
can surface the collection page but not always a single specific photo permalink
for less common queries. `water-infrastructure` and `council-meeting` didn't turn
up one clearly-best individual photo in the search — open the collection link and
pick whichever shot best matches the brand's photography direction (documentary,
natural light, no posed handshakes or generic skyline shots).

## Reminder

This is demo content for Avey.io — the photos just need to look authentically
municipal/infrastructure-related, not be from any real Groundwyre event.
