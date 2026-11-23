# Blog

## How to write a new post

1. Open the `_posts` folder on GitHub and click **Add file → Create new file**.
2. Name the file `YEAR-MONTH-DAY-short-title.md`, for example `2026-12-01-my-first-trip.md`.
3. Paste in this and replace it with your own writing:

   ```
   ---
   title: My First Trip
   ---

   The first paragraph becomes the preview on the home page.

   ## A heading

   More writing. **Bold**, *italics*, [a link](https://example.com).
   ```

4. Click **Commit changes**. The post appears on the site within a minute or two
   (once GitHub Pages is switched on), and the home page list updates itself.

A fuller example with every formatting option is in `_drafts/post-template.md`
(files in `_drafts` are never published).

### Adding a photo
Upload the image into an `images` folder (Add file → Upload files), then either
- put `image: /images/photo.jpg` under the title to make it the post's main photo, or
- put `![]({{ site.baseurl }}/images/photo.jpg)` anywhere in the text to show it there.

## Where things live

| What | File |
|---|---|
| Posts | `_posts/` |
| Banner and menu | `_includes/header.html` |
| Sidebar | `_includes/sidebar.html` |
| Footer | `_includes/footer.html` |
| About page | `about.html` |
| Colours, fonts, spacing | `style.css` |
| Blog name and settings | `_config.yml` |
