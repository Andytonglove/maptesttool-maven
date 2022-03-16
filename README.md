## What's this

Welcome to the MapTestTool-maven. Here is a desktop application tool for map data quality inspection (`地图数据质检工具`). This project is basically the same compared with the MapTestTool, and the only difference is this is built by `Maven` and some changes needed for Maven.

## Aim and Usage

The workspace contains two major function by default, where:

- `地图数据显示`: 可视化显示：地图（栅格/矢量）形式；文本显示：直接显示数据内容。
- `错误记录管理`: 位置标识，错误记录保存，错误记录查询。

## Requirement

>设计开发用于空间数据质量检查的应用软件工具，该工具运行于单PC机桌面环境，不需要网络连接；说明及评估所采用的软件架构风格。

基本功能要求：

- `A、地图数据加载`：从应用中打开指定的图形或文档类型地图数据文件，并显示在应用程序窗口中。

- `B、地图数据显示`：针对不同类型数据采用不同方式：图形形式的可视化符号显示（主要有栅格及矢量格式类型，原型中至少实现其中一种类型的可视化进行示意）；文本形式直接显示数值内容（原型中可用普通文本文件示意）。

- `C、错误记录`:通过在图形中或文本中指定位置，标记各项错误的位置;指出错误位置后，输入错误类型、错误描述等信息并自动给错误编号；在文件中保存所记录的错误信息。

- `D、错误记录查询`：地图数据加载后，在质检工具中打开已保存的错误信息文件，可通过输入关键字搜索并显示出错情况。

## Dependence and Tips

- `GeoTools`：https://www.geotools.org/ 
  `version`：geotools-26.3-bin.zip

- `How to run it`：clone, and new folders named `/bin` and `/lib`, import `GeoTools` jar mentioned before (or you can use Maven) into the folder `/lib` and run main.

## Information

> Using Java, developed in VSCode, built in Maven, by Guan, Doing.
> Github: https://github.com/Andytonglove/MapTestTool