The file gstring.c contains the display string function for SVGAKIT of emx GCC.
The function, g_string (x,y,color,angle,*string), displays the string at (x,y)
which is the upper left corner of the string, in color at an arbitrary angle.
To install, copy gstring.c to SVGAKIT directory and update the files graph.h
and makefile with references to g_string(...), gstring.c and gstring.o.
