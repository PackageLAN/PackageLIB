# PackageLIB
![Version](https://img.shields.io/badge/Version-1.0-brightgreen.svg)&nbsp;&nbsp;![Build](https://img.shields.io/badge/Build-Passed-success.svg)&nbsp;&nbsp;![License](https://img.shields.io/badge/License-AGPL-blue.svg)

&nbsp;&nbsp;&nbsp;&nbsp;这是一个KiCAD 6.0集成库，包含了原理图符号、元器件封装、器件的3D模型和一套配色主题。
其中：
1. 基础的原理图符号参照了GB∕T 4728.5-2018的标准，集成电路的符号使用了[自定义的标准](https://github.com/PackageLAN/PackageLIB/blob/main/PackageSTD.md)（标准攥写中）；
2. 元器件封装参照了JEDEC定义的器件外形尺寸规范，并使用了[自定义的标准](https://github.com/PackageLAN/PackageLIB/blob/main/PackageSTD.md)进行绘制；
3. 3D模型大部分是从KiCAD官方提供的库中复制，部分是从[3D ContentCentral](https://www.3dcontentcentral.cn/)中下载并作一些调整，这个库~~只提供wrl格式的3D模型~~<br>
(考虑可再编辑，3D模型全部更改为默认使用step格式 2022-10-18)；
4. 配色主题的原理图主题引用了[Solarized Light Theme](https://github.com/pointhi/kicad-color-schemes/tree/master/solarized-light)，PCB主题引用了[Nord Theme](https://github.com/pointhi/kicad-color-schemes/tree/master/nord)，并对它们作了部分更改。
5. 它可以通过KiCAD 6.0中新增的包管理工具进行安装（开发中）。

***
