# Profile artwork

`profile-dark.svg` and `profile-light.svg` are self-contained source artwork for the profile README. Edit these SVG files directly; no build or hosted image service is required.

The README selects the artwork using a `picture` element. Each asset has a legible static state. Decorative CSS animation runs once for 3.6 seconds and is disabled by `prefers-reduced-motion: reduce` in supporting browsers. All meaningful information is also present as text in the README.

GitHub sanitises README HTML, so interactions use native links and `details`/`summary`. JavaScript frameworks cannot run in the profile README.
