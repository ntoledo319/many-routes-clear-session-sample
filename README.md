# Clear Session — free local lower third

`lower-third-1080p.html` is a complete static, transparent 1920×1080 overlay. Keep it in a permanent folder. In OBS, add a Browser Source, select **Local file**, choose this HTML, set Width **1920** and Height **1080**, then reset the source transform to its native size. Position it above your underlying scene content in the Sources list. Its navy topic panel should appear near the lower left.

The sample has no script, remote fonts, network requests, countdown or live data. Black/white around the panel in a regular browser is its page background; the surrounding area is transparent in OBS. This is the single-layout HTML sample, not the full offline editor.

To personalize it with a plain text editor, change the visible text inside the `<p class="eyebrow">`, `<h1>` and `<p class="subtitle">` tags. Keep those tags intact and use `&amp;` for an ampersand, `&lt;` for `<` and `&gt;` for `>`. Keep words short. If you edit the CSS colors, verify readable contrast yourself. After saving, refresh the Browser Source in OBS and make a test recording. The embedded configuration metadata documents the original example; manual edits do not update it.

Do not enlarge an 800×600 Browser Source to fill the screen. Use 1920×1080 for this sample. If your base canvas is 1280×720, downscale this source to fit and inspect the recording; the full pack also includes a native 720p export. No automatic font fitting is included in this standalone sample.

You may use or modify the sample in personal/commercial broadcasts under `LICENSE.txt` (MIT). Keep that licence when redistributing the source. No purchase is required.
