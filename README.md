## The 3D surround view on Jetson Tegra TX2 platform - this is my research project for master thesis.
### The essence of the project is the construction of high-quality stitching image from four cameras and projection onto the bowl mesh model with acceptable performance. The project work on ~20 fps with constraints from the connection adaptor 30 fps due the synchronize frames mode. 

### My research papers:
- In progress ...

### Further research topics for this surround view system:
- [ ] Visual odometry
- [ ] Try another mesh model
- [ ] Gradient domain blending
- [ ] Pedestrian detection
- [ ] Obstacles detection
- [ ] Photometric calibration
- [ ] Visual SLAM
- [ ] Automatic parking system

### The 3D view:
<img src="gitresource/demo3dview.gif">

### The top view:
<img src="gitresource/demotopview.gif">

### The hardware setup:
| Device type |  Device name |
|-------------|--------------|
| Camera | e-CAM30A CUMI0330 MOD |
| Connection adaptor board | e-CAM130 TRICUTX2 ADAPTOR |
| Embedded platform | Jetson Tegra TX2 |
| Tripod | - |
### The hardware setup photo:
<img src="gitresource/camerasetup.jpg">

### The software setup:
* OS - Linux Ubuntu LTS v. 16.04
* C++14, GLSL, C CUDA
* CMake >= v3.16
* CUDA Toolkit  v9.0
* V4L2 driver
* OpenGL ES v3.2

### The 3d party library:
* [OpenCV v. 4.1.2](https://github.com/opencv/opencv)
* [Mesa 3D (EGL, GLES)](https://docs.mesa3d.org/download.html)
* [GLM](https://github.com/g-truc/glm)
* [stb_image](https://github.com/nothings/stb)
* [GLFW](https://www.glfw.org)
* [ASSIMP v4.0.1](https://www.assimp.org/index.php/downloads)

### [Car model](https://www.cgtrader.com/free-3d-models/car/sport/low-poly-dodge-challenger-srt-hellcat-2015)