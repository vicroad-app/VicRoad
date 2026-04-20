Per-link profiles (local files)

How it works
1. Put photos in user-photos/.
2. Create a file profiles/<id>.json.
3. Open the site with ?id=<id>.

Example
- profiles/john.json
- Link: https://nickolasdaniel707-hue.github.io/VicRoad/?id=john

Profile fields
- licence_photo_url: Replaces b83abeb89_IMG_6942.jpg
- paste_selector: CSS selector to paste image into a specific element (example: .text-gray-400)
- paste_index: Which matched element to use when selector matches multiple elements (0-based)
- paste_photo_url: Optional photo URL/path for selector paste (falls back to licence_photo_url)
- logo_url: Replaces 469154745_outline.png
- nav_icon_url: Replaces 29b561457_IMG_6936-removebg-preview1.png
- signature_photo_url: Replaces ed3f288cd_IMG_6899.jpg
- replacements: Map any source filename to a custom image URL/path

Paths
- Use relative paths like ../user-photos/john-licence.jpg
- You can also use full https URLs
