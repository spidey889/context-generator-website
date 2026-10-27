# Context Generator Website

The Cap Context homepage, finished videos, poster and only the shared images needed by the homepage. This is a plain static site with no npm dependencies or build step.

- Production website: https://spreadz.in/
- Vercel production: https://context-generator-website.vercel.app/
- GitHub Pages: https://spidey889.github.io/context-generator-website/ (`main`, repository root)
- Vercel project: `context-generator-website`, team `vinits-projects-9bc84d4f`; production branch `main`.

`index.html` embeds `brag/brag.mp4` with `brag/brag.jpg` as its poster. The earlier `2026-05-10 09-51-15.mp4` is retained as a separate finished video. The small `extension/` directory contains six shared PNGs only; it is not an installable extension. Existing source terms are in `LICENSE`.

Privacy, analysis, the extension/backend and **all video-making tools and editable sources** remain in [context-generator](https://github.com/spidey889/context-generator). Recreate videos there using `brag/README.md`, then publish only the resulting MP4/JPG files here. Do not copy Python scripts, rendering code, reference files, caches or the whole `brag/` folder into this repository.

Vercel's `vercel.json` keeps privacy and analysis at their existing `spreadz.in` URLs while reading their files and two dependent images from the original backend deployment. Keep the explicit analysis rules: an earlier wildcard failed for the trailing-slash URL. GitHub Pages serves the static homepage independently; its Privacy Policy link uses the original public address.

**The website move must not add any Chrome extension permissions.** Keep the extension manifest and backend address unchanged. Never add this repository's or this Vercel project's hostnames to the extension.

During the domain transition, the previous copy stays available until the real public URLs have been verified. Domain/DNS status is recorded in the original repository's migration audit.
