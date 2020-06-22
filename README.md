# Image converter for LVGL

`lv_img_conv` is a new image converter for LVGL, designed to replace the previous PHP converter at https://github.com/lvgl/lv_utils/blob/master/img_conv_core.php.

Example usage:

```
./lv_img_conv.js logo_lvgl.png -f -c CF_TRUE_COLOR_ALPHA
```

A file called `logo_lvgl.c` will be created in the same directory.
