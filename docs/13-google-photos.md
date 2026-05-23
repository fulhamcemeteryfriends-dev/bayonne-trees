# Using Google Photos for tree photos

If your group already keeps photos in Google Photos, you can link to
them directly from your tree map — no need to download and re-upload
the files.

The catch: **the photo must be in a shared album**. Photos in a
personal library have private URLs that only the photo's owner (or
whoever you've shared with) can see, so they won't display on the map
for visitors.

## How to spot a usable URL

After you've copied the image URL, look at the start of it:

- ✅ **`lh3.googleusercontent.com/…`** (or `lh4`, `lh5`, `lh6` —
  Google rotates the number) is the **public** form served from a
  shared album. This will work on the map.
- ❌ **`fife.googleusercontent.com/…`** is the **private** form served
  from a personal library. Visitors will see a broken image. If you
  see `fife`, the photo isn't yet in a shared album — follow the
  steps below.

## Step-by-step

1. Open Google Photos and find the photo.
2. Click the **Share** icon → *Shared albums* → pick an existing
   shared album, or click **New shared album**. (Anyone-with-the-link
   is fine; you don't need to invite anyone.)
3. Open the photo from inside the shared album.
4. Right-click → **Copy image address** (on mobile: tap the share icon
   → **Copy link**, then open the link in a browser and right-click the
   image).
5. Paste the URL into the `Photos` cell of the tree's row in your
   spreadsheet.

If the URL starts with `lh3` (or `lh4`/`lh5`/`lh6`), you're done —
refresh your map and the photo will appear.

## Heads-up

- If you ever delete the shared album, or remove the photo from it,
  the image stops loading on the map. The URL still exists but
  resolves to nothing.
- Google sometimes regenerates the URL when albums are restructured.
  If a photo suddenly stops displaying, re-copy the image address.
