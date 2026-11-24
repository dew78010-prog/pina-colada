PINA COLADA GALLERY FIX

1) Open your GitHub repository:
   https://github.com/dew78010-prog/pina-colada

2) Upload gallery.js to the ROOT of the repository
   (same level as index.html, gallery.html and gallery.css).

3) Open index.html in GitHub and tap the pencil/Edit button.
   Find this exact text:
      <a href="#gallery">Gallery</a>
   Replace it with:
      <a href="gallery.html">Gallery</a>

   Save/Commit the change.

4) Wait 1-3 minutes, then open:
   https://dew78010-prog.github.io/pina-colada/gallery.html

IMPORTANT:
- Do not put gallery.js inside a folder.
- Keep gallery.html and gallery.css in the repository root.
- This fixes the missing JavaScript that prevented reveal animations,
  photo filters, and the fullscreen photo viewer from working.
- The Tuk Tuk filter will show its "Coming soon" message until tuk-tuk
  photos are added.
