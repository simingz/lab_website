---
# Files in this folder represent a Widget Page (homepage)
type: widget_page

# Homepage is headless, other widget pages are not.
headless: true

design:
  background:
    image:
      # Name of image in `assets/media/`.
      filename: genes.jpg
      # Apply image filters?
      filters:
        # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
        brightness: 0.6
      #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
      size: cover
      # Image focal point. Options include `left`, `center` (default), or `right`.
      position: center
      # Use a fun parallax-like fixed background effect on desktop? true/false
      parallax: true
      # Text color (true=light, false=dark, or remove for the dynamic theme color).
      text_color_light: true

---

