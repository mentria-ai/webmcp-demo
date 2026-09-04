# mentria.ai - WebMCP Challenge submission snapshot

**Main repository: https://github.com/mentria-ai/website** - full source, history,
and active development live there.

This repository is a frozen snapshot build of [mentria.ai](https://mentria.ai),
submitted to the WebMCP Challenge and served at https://webmcp.mentria.ai/ for the
judging period only (until 2026-09-21 5:00 PM PT). It corresponds to tag
`webmcp-submission` (commit ec54a8f) in the main repository and will not change
while judging runs.

The site is built with Eleventy and plain JavaScript - no bundler, so the files here
are the readable source as served. WebMCP integration points:

- `assets/js/mentria-webmcp.js` - tool registration bridge (document.modelContext)
- `assets/js/mentria-bus.js` - cross-context capability bus behind the bridge
- `tools/console/index.html` - the on-device AI console agent that drives the site

MIT licensed.
