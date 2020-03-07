# matrix_3D
3d matrix calculations, can be used for 3d matrix manipulation, library is header only, written in C++, tested with QT, but can
be used cross platform and is Codeblocks compatible.

-No licence
-Free to use

Usage:
- #include <matrix_3d.h>
- vec3d translate = translate_3d(50,5,0,10,0,0);
- vec3d scale     = scale_3d(50,10,30,2);
- vec3d rotate    = rotate_3d(1,0,0,0,30,53.1);
- vec3d mirror    = mirror_3d(10,0,0,0,1,0);
- vec3d shear_x   = shearing_3d(1,1,2,2,2,3,1,0,0); //will shear in x axis ==> output : after shearing = (1, 3, 5).
- vec3d shear_y   = shearing_3d(1,1,2,2,2,3,0,1,0); //will shear in y axis.
- vec3d shear_z   = shearing_3d(1,1,2,2,2,3,0,0,1); //will shear in z axis.

![0](https://raw.githubusercontent.com/grotius-cnc/matrix_3D/master/3D-Transformation-in-Computer-Graphics.png)
