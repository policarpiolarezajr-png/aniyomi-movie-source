# Source implementation checklist

Before implementing a source for a website you are authorized to integrate:

1. Confirm the site has permission/licensing for the media it hosts.
2. Inspect the normal HTML for:
   - movie cards on the listing page
   - title, poster, and detail-page URL
   - pagination format
   - search URL/query format
   - description and metadata on detail pages
3. Use stable CSS selectors; avoid depending on rotating class names.
4. Add normal error handling for empty pages, HTTP failures, and changed layouts.
5. For playback, use only direct media URLs that the site is authorized to expose and that Aniyomi's API supports. Do not bypass DRM, access controls, paywalls, or anti-bot protections.
6. Verify compatibility with the current `extensions-lib` API and test on a device.

The `123moviesfree.net` page could not be inspected here, so selectors and playback support cannot be responsibly guessed.
