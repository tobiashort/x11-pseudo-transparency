```
picom \
  --backend xrender \
  --transparent-clipping \
  --transparent-clipping-exclude "window_type = 'menu'" \
  --transparent-clipping-exclude "window_type = 'dropdown_menu'" \
  --transparent-clipping-exclude "window_type = 'popup_menu'" \
  --transparent-clipping-exclude "window_type = 'tooltip'" \
  --transparent-clipping-exclude "window_type = 'utility'" \
  --no-fading-openclose \
  --opacity-rule '95:class_g="st-256color"'
```
