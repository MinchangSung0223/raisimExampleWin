# raisimExampleWin

1. Install CMake
   windows:  https://github.com/Kitware/CMake/releases/download/v3.26.4/cmake-3.26.4-windows-x86_64.msi
3. Install raisimLib
   1) License : https://raisim.com/sections/License.html , https://docs.google.com/forms/d/e/1FAIpQLScNL0vbZPDNS93L6Jv6fgR51WTsvXxfhnVOtKDVRdAmHIoG4w/viewform
   2) github : https://github.com/raisimTech/raisimLib
   3) Unreal Visualizer : https://github.com/raisimTech/raisimLib/releases/tag/v1.1.5 , 10016version
5. Install
  ```bash
   git clone https://github.com/MinchangSung0223/raisimExampleWin.git
   mkdir build
   cd build
   cmake ..
   cmake-gui .
 ```
 ![image](https://github.com/MinchangSung0223/raisimExampleWin/assets/53217819/c1ee7769-d73f-4518-8abf-70c7f1951e04)

  raisim_path :  C:\Users\USERNAME\raisim_ws\raisimLib\raisim\win32\lib\cmake\raisim
  ![image](https://github.com/MinchangSung0223/raisimExampleWin/assets/53217819/97957625-04c3-4d1b-8e6b-49e036fd7508)

  Eigen3_path : C:\Users\USERNAME\raisim_ws\raisimLib\thirdParty\Eigen3\share\eigen3\cmake
  
  ![image](https://github.com/MinchangSung0223/raisimExampleWin/assets/53217819/7f96c432-9b29-4afc-94c6-16115442130d)


```bash
  cmake --build . --config Release
```
