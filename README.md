# JunkBox_Lib++
C++ Static Library for VC++

if you want to use it on Linux, please use C++Lib in JunkBox_Lib

## DownLoad
```
git clone https://github.com/JunkBox-Library/JunkBox_Libpp.git JubkBox_Lib++
```

## Needed External Tool
### Visual Studio Comminity 2022 (VC++)

## Recommended External Libraries
* of course, you can use another libraries (requires JunkBox_Lib++_2022.vcxproj configuration change)
### OpenJpeg
* x64: **openjpeg-v2.5.0-windows-x64.zip**
* x86: **openjpeg-v2.5.0-windows-x86.zip**
  * https://github.com/uclouvain/openjpeg/releases/

### Jpeg
* **jpegsr9e.zip** (source code)
  * https://www.ijg.org/files
  * [how to compile](https://github.com/JunkBox-Library/JunkBox_Libpp/wiki/libjpeg)

### zlib
* **zlib-1.3.tar.gz** (source code)
   * https://www.zlib.net/
   * compile using cmake-gui and VS Community

### libpng
* **libpng-1.6.43.tar.gz** (source code)
  * http://www.libpng.org/pub/png/libpng.html
  * https://sourceforge.net/projects/libpng/files/libpng16/1.6.43/
  * compile using cmake-gui and VS Community
 
### Location of the folders (default)
* jpeg-9e
* JunkBox_Lib++
* openjpeg-v2.5.0-windows-x64
* openjpeg-v2.5.0-windows-x86
* zlib-1.3
* lpng16

### Development Environment (OpenJpeg, Jpeg, zlib, libpng)
* [JunkBox_Lib++_devel_env.zip](https://blackjack.nsl.tuis.ac.jp/Download/Release/JunkBox_Lib++_devel_env_1.10.zip)

## Compile
* double click **JunkBox_Lib++_2022.vcxproj**
* build targets

### Lib Pragma for VC++
#### OpenJpeg (GraphLib/Jpeg2KTool.h)
* < v2.0
  * Release: **OpenJPEG.lib**
  * Debug: **OpenJPEGd.lib**
* \>=2.0
  * **openjp2.lib**
 
#### Jpeg (GraphLib/JpegTool.h)
* **libjpeg.lib**

#### zlib (ExtendLib/xLib/gz_tool.h)
* Release: **zlib.lib**
* Debug: **zlibd.lib**
 
#### png (GraphLib/PngTool.h) Static Link
* Release: **libpng16_static.lib**
* Debug: **libpng16_staticd.lib**

#### OpenCV (GraphLib/OpenCVTool.h)
* Release: **opencv_core242.libb**, **opencv_imgproc242.lib**, **opencv_objdetect242.lib**
* Debug: **opencv_core242d.libb**, **opencv_imgproc242d.lib**, **opencv_objdetect242d.lib**

## Documents
* [Wiki](https://polaris.star-dust.jp/pukiwiki/?JunkBox_Lib%2B%2B)
* [Doxygen](https://polaris.star-dust.jp/doxygen/JunkBox_Lib%2B%2B/)

