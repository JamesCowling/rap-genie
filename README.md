# rap-genie

- Load the databae from `load.py`.
- Extract verses and generate embeddings with `processSongBatch({limit: 50, recursive: true, minViews: 500000n})`.
- Run Convex sync with `npx convex dev`.
- Host website with `npx vite`.

## TODO

- get a domain name and host site. rapgenie.net?
- add link to github repo and convex
- change mascot to something more cartoony
- introduce some kind of filtering or ranking by popularity
- look up album art for each song with genius api
