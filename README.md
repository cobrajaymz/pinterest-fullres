# Pin Full-Res

Pinterest serves resized copies of images (236px, 474px, 736px wide) even when
a bigger original exists on their CDN. This tool takes a Pinterest image or
pin link, tests the available size buckets, and keeps whichever one actually
resolves at the highest resolution — no guessing, no scraping.

It also links each result out to Google Lens, Yandex, and TinEye's reverse
image search, since Pinterest images are usually re-posts and the original
host (photographer, stock site, blog) sometimes has an even bigger file.

**Usage:** paste one or more Pinterest links (one per line) and click
"Find originals." Works best with direct `i.pinimg.com` links; pin page
links (`pinterest.com/pin/...`) are resolved on a best-effort basis.
