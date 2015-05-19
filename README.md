Create Firefox Image With Version
=================================

Create a firefox icon with version number in the icon.

This was created to be used for generating version-based icons for
[Install All Firefoxes](https://github.com/omgmog/install-all-firefox) shell
script for OS X.

Requires ImageMagick and Ghostscript.

```bash
$ brew install imagemagick gs
```

To use:

```bash
$ create_firefox_image_with_version "26.0" fx26.png"
```

Note: Use png as file extension or you will get no transparency goodness.

Output:

![](http://f.cl.ly/items/1q0c210Y0A193U3p2I26/fx26.png)
