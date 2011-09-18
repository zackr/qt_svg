About **qt_svg**
==================

qt_svg is a trivial app rendering scaling/rotating
SVG using Qt's OpenGL code and showing the fps.
It's made to follow NVIDIA nvpr_svg code from
http://developer.nvidia.com/nv-path-rendering

The repository also has a patch to nvpr_svg which
makes it open a new window and use Qt OpenGL instead
of the raster engine to render the content.

You can start qt_svg by simply typing

    ./qt_svg

After applying a patch to nvpr_svg you can start
it as:

    ./nvpr_svg -nosync -svg svg/complex/tiger.svg -spin -animate

right click on the window select
"Toggle Cairo/Qt software rendering"
and click on the newly creted window.
