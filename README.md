# Context Generator Website

Public repository for the Cap Context homepage and its videos.

## Setup stage — 2026-10-27

This repository currently contains only a small hosting placeholder. The real homepage, videos and assets have not been copied or moved.

- GitHub Pages source: `main`, repository root. Default URL: https://spidey889.github.io/context-generator-website/
- Vercel project: `context-generator-website`, in `vinits-projects-9bc84d4f`, connected to this repository's `main` branch.
- No custom domain cutover is part of this setup. The existing `spreadz.in` site continues to use the original repository.

## Next stage: move the minimum

Move only the original root `index.html`, the videos and the files actually required by that homepage. Keep privacy, `analysis/`, the extension and the backend in https://github.com/spidey889/context-generator.

**Highest priority: introduce no new extension permissions, site access or runtime permission prompts.** Preserve the existing `spreadz.in/analysis*` and legacy analysis bridge matches and the backend address `https://context-generator-five.vercel.app`. Website hosting does not require adding the new repository or Vercel domain to the extension manifest. Compare the final extension package with the published package before any extension release.

The later domain cutover must preserve the existing public analysis and privacy URLs while their files remain in the original repository. Plan and verify that routing before switching `spreadz.in`.

Chrome rules: [permission warnings](https://developer.chrome.com/docs/extensions/develop/concepts/permission-warnings), [permission declarations](https://developer.chrome.com/docs/extensions/develop/concepts/declare-permissions).
