# Aniyomi Movie Source — Starter Template

This is a **starter project**, not a ready-to-install APK. It shows the basic shape of an Aniyomi online source for a site you own or are authorized to access.

## Important
- The supplied `123moviesfree.net` site could not be inspected reliably from this environment.
- This template intentionally does **not** extract or bypass third-party streaming links, DRM, paywalls, anti-bot protections, or access controls.
- Aniyomi extensions must be built against a compatible Aniyomi extensions repository/API. This folder alone is not a complete Gradle build.
- Site-specific CSS selectors and video handling must be implemented and tested for a lawful source.

## Files
- `MovieSource.kt` — example source skeleton with placeholders for list/search/details.
- `SOURCE_NOTES.md` — what to inspect and fill in.
- `build.gradle.example` — extension module metadata example.

## How to use
1. On a computer, install Android Studio and Git.
2. Clone a current compatible Aniyomi extensions project, following that project's own contribution/build guide.
3. Add a module under `src/en/moviedemo/` and adapt the example Kotlin class to the current API version.
4. Replace the placeholder selectors with selectors from a site you own or have permission to integrate.
5. Build and test on a device with Aniyomi installed.

A compiled APK is not included because this starter has not been compiled or tested against your exact Aniyomi version.
