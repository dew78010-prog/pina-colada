PINA COLADA — CINEMATIC GALLERY PACKAGE
=======================================

FILES
-----
gallery.html   The separate gallery page
gallery.css    All gallery styling and animations
gallery.js     Filters, scroll reveals and fullscreen photo viewer

INSTALL ON GITHUB (PHONE)
-------------------------
1. Download and extract this ZIP on your phone.
2. Open your GitHub repository:
   dew78010-prog / pina-colada
3. Upload gallery.html, gallery.css and gallery.js to the SAME ROOT LEVEL
   as index.html. Do not put them inside another folder.
4. Your existing photos are already in the repository root. Do not upload
   duplicate copies of those images.
5. Open index.html in GitHub and tap Edit.
6. Find this existing navigation link:
      <a href="#gallery">Gallery</a>
   Replace it with:
      <a href="gallery.html">Gallery</a>
   Save/commit the change.
7. Open the new page:
   https://dew78010-prog.github.io/pina-colada/gallery.html

ANIMATIONS INCLUDED
-------------------
- Cinematic hero image zoom and header entrance
- Smooth scroll reveal with staggered gallery cards
- Image hover/touch zoom
- Category filters
- Fullscreen photo lightbox with animated open/close
- Previous/next controls, keyboard arrows and mobile swipe
- Reduced-motion accessibility support

ADD TUK TUK PHOTOS LATER
------------------------
1. Upload your tuk tuk photo (example: tuk-tuk-01.jpg) to the repository
   root, beside index.html.
2. Open gallery.html and find the section with id="photoGrid".
3. Copy one existing <article class="photo-card ..."> block, paste it
   inside photoGrid, and update:
      data-category="surf"       to       data-category="tuk"
      data-src="..."             to       data-src="tuk-tuk-01.jpg"
      the image src and alt text
      the title text and caption
4. The "Tuk Tuk Service" filter will then show that photo automatically.

IMPORTANT
---------
- Keep your current style.css unchanged.
- Keep your current main index.html except for the one navigation-link
  replacement shown above.
- This gallery uses your existing image filenames:
  beach-coconuts.jpg, surf-lessons.jpg, surf-school.jpg,
  surf-instructor.jpg and surf-lesson.jpg.
- If one of these filenames is different in your GitHub repository, change
  the matching src/data-src filename in gallery.html to the exact filename.
