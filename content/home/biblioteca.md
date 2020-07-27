+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true       # This file represents a page section.
active = true         # Activate this widget? true/false
weight = 100          # Order that this section will appear.

title = "Biblioteca Popular"
subtitle = "Por mas aperturismo ideológico"

[content]
  # Page type to display. E.g. project.
  page_type = "biblioteca"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  [[content.filter_button]]
    name = "Todos"
    tag = "*"
  
  [[content.filter_button]]
    name = "José Martí"
    tag = "coleccion1"
  
  [[content.filter_button]]
  name = "Leer en libertad"
    tag = "brigada"
    
[[content.filter_button]]
  name = "Casa de las Américas"
    tag = "coleccion3"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = true

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  color = "#123045 !important"
  
  # Background gradient.
  # gradient_start = "rgb(63, 76, 107) 80%"
  # "DeepSkyBlue"
  # gradient_end = "rgb(96, 108, 136) 30%"
  # "SkyBlue"
  
  # Background image.
  # image = "biblioteca.webp"  # Name of image in `static/img/`.
  # image_darken = 0.8         # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = "" 
 
 # CSS class.
 css_class = ""
+++

