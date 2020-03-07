# matrix_3D
3d matrix calculations, can be used for 3d matrix manipulation, library is header only, written in C++, tested with QT, but can
be used cross platform and is Codeblocks compatible.

Usage:
  #include <matrix_3d.h>
  vec3d trans0=translate_3d(50,5,0,10,0,0);
  vec3d scale0=scale_3d(50,10,30,2);
  vec3d rot0=rotate_3d(1,0,0,0,30,53.1);
  vec3d mir0 = mirror_3d(10,0,0,0,1,0);
  vec3d shear0 = shearing_3d(1,1,2,2,2,3,1,0,0); //will shear in x axis ==> output : after shearing = (1, 3, 5).
  vec3d shear0 = shearing_3d(1,1,2,2,2,3,0,1,0); //will shear in y axis
  vec3d shear0 = shearing_3d(1,1,2,2,2,3,0,0,1); //will shear in z axis

Library functions visualized:
![1](https://raw.githubusercontent.com/grotius-cnc/matrix_3D/master/3D-Transformation-in-Computer-Graphics.png)

Matrix model :
  - translation (move)
  
![2](https://raw.githubusercontent.com/grotius-cnc/matrix_3D/master/3D-Translation-Matrix-in-Computer-Graphics-1.png)
 
  - Rotation :
![3](https://raw.githubusercontent.com/grotius-cnc/matrix_3D/master/3D-Rotation-Matrix-in-Computer-Graphics-X-Axis-Rotation-1.png)
![4](https://raw.githubusercontent.com/grotius-cnc/matrix_3D/master/3D-Rotation-Matrix-in-Computer-Graphics-Y-Axis-Rotation-1.png)
![5](https://raw.githubusercontent.com/grotius-cnc/matrix_3D/master/3D-Rotation-Matrix-in-Computer-Graphics-Z-Axis-Rotation.png)
 
  - Scaling :

![6](https://raw.githubusercontent.com/grotius-cnc/matrix_3D/master/3D-Scaling-Matrix-in-Computer-Graphics.png)
  
  - Reflection :
![7](https://raw.githubusercontent.com/grotius-cnc/matrix_3D/master/3D-Reflection-Matrix-in-Computer-Graphics-Reflection-Relative-to-XY-Plane-1.png)
![8](https://raw.githubusercontent.com/grotius-cnc/matrix_3D/master/3D-Reflection-Matrix-in-Computer-Graphics-Reflection-Relative-to-XZ-Plane-1.png)
![9](https://raw.githubusercontent.com/grotius-cnc/matrix_3D/master/3D-Reflection-Matrix-in-Computer-Graphics-Reflection-Relative-to-YZ-Plane.png)

- Shear (3d model transform) :

![10](https://raw.githubusercontent.com/grotius-cnc/matrix_3D/master/3D-Shearing-Matrix-in-Computer-Graphics-Shearing-in-X-Axis-1.png)
![11](https://raw.githubusercontent.com/grotius-cnc/matrix_3D/master/3D-Shearing-Matrix-in-Computer-Graphics-Shearing-in-Y-Axis.png)
![12](https://raw.githubusercontent.com/grotius-cnc/matrix_3D/master/3D-Shearing-Matrix-in-Computer-Graphics-Shearing-in-Z-Axis.png)
