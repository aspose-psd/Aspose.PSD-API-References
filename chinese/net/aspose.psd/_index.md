---
title: "Aspose.PSD"
second_title: "Aspose.PSD for .NET API 参考"
description: "该命名空间是嵌套命名空间的核心，也是用于 Aspose.PSD 处理的最基本对象。"
type: docs
weight: 10
url: /zh/net/aspose.psd/
---
{{< psd/tize >}}
该命名空间是嵌套命名空间的核心，也是用于 Aspose.PSD 处理的最基本对象。

## 类

| 类 | 描述 |
| --- | --- |
| [AggregateException](./aggregateexception/) | 聚合多个异常。 |
| [Blend](./blend/) | 定义混合模式。此类不可继承。 |
| [Brush](./brush/) | 基础画笔类。 |
| [BuildVersionInfo](./buildversioninfo/) | 包含当前构建版本信息。 |
| [Cache](./cache/) | 包含缓存设置。 |
| [CmykColorHelper](./cmykcolorhelper/) | 帮助方法用于处理以有符号 32 位整数表示的 CMYK 颜色。提供与 [`CmykColor`](../aspose.psd/cmykcolor/) 结构体相似的 API。由于 CMYK 颜色仅以 Int32 而非包含内部字段的结构体呈现，因此更轻量。请在可能的情况下优先使用此类的静态方法，而不是已弃用的 [`CmykColor`](../aspose.psd/cmykcolor/) 结构体。 |
| [ColorBlend](./colorblend/) | 定义用于在多色渐变中插值颜色混合的颜色和位置数组。此类不可继承。 |
| [ColorMap](./colormap/) | 定义颜色转换映射。[`ImageAttributes`](../aspose.psd/imageattributes/) 类的多个方法通过使用颜色重新映射表（即 [`ColorMap`](../aspose.psd/colormap/) 结构体数组）来调整图像颜色。不可继承。 |
| [ColorMatrix](./colormatrix/) | 定义包含 RGBA 空间坐标的 5×5 矩阵。[`ImageAttributes`](../aspose.psd/imageattributes/) 类的多个方法通过使用颜色矩阵来调整图像颜色。此类不可继承。 |
| [ColorPalette](./colorpalette/) | 定义组成调色板的颜色数组。这些颜色为 32 位 ARGB 颜色。不可继承。 |
| [ColorPaletteHelper](./colorpalettehelper/) | 用于调色板操作的帮助类。 |
| [ColorTranslator](./colortranslator/) | 在 GDI+ Color 结构之间相互转换颜色。此类不可继承。 |
| [CompositeException](./compositeexception/) | 复合异常 |
| [CustomLineCap](./customlinecap/) | 封装自定义用户定义的线帽。 |
| [DataStreamSupporter](./datastreamsupporter/) | 数据流容器。 |
| [DisposableObject](./disposableobject/) | 表示一次性对象。 |
| [Figure](./figure/) | 图形。形状的容器。 |
| [FileStreamContainer](./filestreamcontainer/) | 文件流处理助手。 |
| [Font](./font/) | 定义文本的特定格式，包括字体、大小和样式属性。此类不可继承。 |
| [FontSettings](./fontsettings/) | 通用 PSD 矢量格式渲染器字体设置。 |
| [Graphics](./graphics/) | 根据当前程序集使用的图形引擎表示图形。 |
| [GraphicsPath](./graphicspath/) | 表示一系列相连的直线和曲线。此类不可继承。 |
| [Image](./image/) | 图像是所有类型图像的基类。 |
| [ImageAttributes](./imageattributes/) | [`ImageAttributes`](../aspose.psd/imageattributes/) 对象包含有关在渲染期间如何操作位图和元文件颜色的信息。[`ImageAttributes`](../aspose.psd/imageattributes/) 对象维护多个颜色调整设置，包括颜色调整矩阵、灰度调整矩阵、伽马校正值、颜色映射表和颜色阈值。在渲染过程中，颜色可以被校正、加暗、增亮和移除。要应用这些操作，请初始化一个 [`ImageAttributes`](../aspose.psd/imageattributes/) 对象，并将该 [`ImageAttributes`](../aspose.psd/imageattributes/) 对象的路径（以及 [`Image`](../aspose.psd/image/) 对象的路径）传递给 DrawImage 方法。 |
| [ImageCreatorsRegistry](./imagecreatorsregistry/) | 表示图像创建者注册表。 |
| [ImageExportersRegistry](./imageexportersregistry/) | 表示图像导出器注册表。 |
| [ImageLoadersRegistry](./imageloadersregistry/) | 表示图像加载器注册表。 |
| [ImageOptionsBase](./imageoptionsbase/) | 图像基础选项。 |
| [ImageResizeSettings](./imageresizesettings/) | 图像大小调整设置类 |
| [IntRange](./intrange/) | 表示元素序列的类 |
| [License](./license/) | 提供对组件授权的方法。 |
| [LoadOptions](./loadoptions/) | 表示加载选项。 |
| [Matrix](./matrix/) | 替换 GDI+ 矩阵。 |
| [Metered](./metered/) | 提供设置计量密钥的方法。 |
| [NonGenericDictionary](./nongenericdictionary/) | 表示非泛型字典。 |
| [NonGenericList](./nongenericlist/) | 非泛型对象列表 |
| [ObjectWithBounds](./objectwithbounds/) | 具有边界的对象。 |
| [OpenTypeFontsCache](./opentypefontscache/) | 系统中已安装的 OpenType 字体的缓存。 |
| [Pen](./pen/) | 定义用于绘制直线、曲线和图形的对象。 |
| [PixelDataFormat](./pixeldataformat/) | 像素数据格式。这是一个不可变对象。 |
| [PixelsData](./pixelsdata/) | 用于存储图像像素数据及其边界的类。 |
| [PluginLicenseException](./pluginlicenseexception/) | 插件许可证异常 |
| [ProgressEventHandler](./progresseventhandler/) | 进度事件处理函数引用 |
| [RasterCachedImage](./rastercachedimage/) | 表示支持光栅图形操作的光栅图像。需要时，此图像会缓存像素数据。 |
| [RasterImage](./rasterimage/) | 表示支持光栅图形操作的光栅图像。 |
| [RawDataSettings](./rawdatasettings/) | 原始数据设置 |
| [Region](./region/) | 描述由矩形和路径组成的图形形状的内部。此类不可继承。 |
| [ResolutionSetting](./resolutionsetting/) | 图像保存选项的分辨率设置。 |
| [Shape](./shape/) | 形状。使用特定规则连接的一组连续点。 |
| [ShapeSegment](./shapesegment/) | 表示形状段。段是连接两个点的直线或曲线。 |
| [Source](./source/) | 源用于包含对象管道的所有相关信息。 |
| [SplitStreamContainer](./splitstreamcontainer/) | 表示分割流容器，包含流并提供流处理例程。 |
| [StreamContainer](./streamcontainer/) | 表示流容器，包含流并提供流处理例程。 |
| [StringFormat](./stringformat/) | 封装文本布局信息（如对齐、方向和制表位）、显示操作（如省略号插入和数字本地化替换）以及 OpenType 特性。此类不可继承。 |
| [TransparencySupporter](./transparencysupporter/) | 支持透明度的对象。 |
| [VectorImage](./vectorimage/) | 矢量图像是所有类型矢量图像的基类。 |
## Structures

| 结构 | 描述 |
| --- | --- |
| [CmykColor](./cmykcolor/) | 像素的 CMYK 颜色。 |
| [Color](./color/) | 像素的颜色。 |
| [Point](./point/) | 表示整数 x、y 坐标的有序对，定义二维平面上的一点。 |
| [PointF](./pointf/) | 表示浮点数 x、y 坐标的有序对，定义二维平面上的一点。 |
| [Rectangle](./rectangle/) | 存储表示矩形位置和大小的四个整数。 |
| [RectangleF](./rectanglef/) | 存储一组四个浮点数，表示矩形的位置和大小。 |
| [Size](./size/) | 表示大小。 |
| [SizeF](./sizef/) | 存储一对有序的浮点数，通常表示矩形的宽度和高度。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IAdvancedBufferProcessor](./iadvancedbufferprocessor/) | 高级缓冲区处理器。 |
| [IBufferProcessor](./ibufferprocessor/) | 缓冲区处理器。 |
| [IColorConverter](./icolorconverter/) | 颜色转换器。 |
| [IColorPalette](./icolorpalette/) | 颜色调色板接口。 |
| [IImageCreator](./iimagecreator/) | 图像创建器。 |
| [IImageCreatorDescriptor](./iimagecreatordescriptor/) | 图像创建器描述符，指定创建器属性。创建器描述符用于克服在内存中保留每个图像创建器实例以及多线程问题的必要性。 |
| [IImageDescriptor](./iimagedescriptor/) | 图像描述符。包含所有其他图像描述符类型的基础属性和方法。 |
| [IImageExporter](./iimageexporter/) | 图像导出器。可以将内部 Aspose.PSD 格式的数据导出为指定的数据格式。 |
| [IImageExporterDescriptor](./iimageexporterdescriptor/) | 表示图像导出器描述符。导出器描述符用于克服在内存中保留每个导出器实例以及多线程问题的必要性。 |
| [IImageLoader](./iimageloader/) | 图像加载器。 |
| [IImageLoaderDescriptor](./iimageloaderdescriptor/) | 图像加载器描述符，指定加载器属性。加载器描述符用于克服在内存中保留每个图像加载器实例以及多线程问题的必要性。 |
| [IIndexedColorConverter](./iindexedcolorconverter/) | 用于索引图像格式的颜色转换器。 |
| [IKeyedObject](./ikeyedobject/) | 表示具有键的对象的接口。 |
| [IObjectWithBounds](./iobjectwithbounds/) | 表示具有边界的对象。 |
| [IOrderedShape](./iorderedshape/) | 表示有序形状。有序形状是一组连续的点，具有起始点和结束点。该连续点集使用特定规则连接。 |
| [IPartialArgb32PixelLoader](./ipartialargb32pixelloader/) | 符合部分加载的 32 位 ARGB 像素。 |
| [IPartialArgb64PixelLoader](./ipartialargb64pixelloader/) | 64 位 ARGB 像素加载器。 |
| [IPartialPixelLoader](./ipartialpixelloader/) | 符合部分加载的像素。 |
| [IPartialRawDataLoader](./ipartialrawdataloader/) | 部分数据加载器。 |
| [IPsdColorPalette](./ipsdcolorpalette/) | pasd 颜色调色板 |
| [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader/) | 光栅图像 32 位 ARGB 像素加载器。 |
| [IRasterImagePixelLoader](./irasterimagepixelloader/) | 光栅图像像素加载器。 |
| [IRasterImageRawDataLoader](./irasterimagerawdataloader/) | 光栅图像原始数据加载器。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [CacheType](./cachetype/) | 指定要使用的缓存类型。 |
| [CharacterSet](./characterset/) | 表示使用的字符集。 |
| [ColorAdjustType](./coloradjusttype/) | 指定哪些对象使用颜色调整信息。 |
| [ColorChannelFlag](./colorchannelflag/) | 指定 CMYK（青色、品红、黄色、黑色）颜色空间中的各个通道。此枚举由 SetOutputChannel 方法使用。 |
| [ColorCompareMethod](./colorcomparemethod/) | 用于调整到最近邻的颜色比较方法 |
| [ColorMatrixFlag](./colormatrixflag/) | 指定将受到 [`ImageAttributes`](../aspose.psd/imageattributes/) 的颜色和灰度调整设置影响的图像和颜色类型。 |
| [ColorQuantizationMethod](./colorquantizationmethod/) | 颜色量化方法 |
| [CompositingQuality](./compositingquality/) | 指定在合成期间使用的质量级别。 |
| [DashCap](./dashcap/) | 指定在虚线的每段破折号两端使用的图形形状类型。 |
| [DashStyle](./dashstyle/) | 指定使用 [`Pen`](../aspose.psd/pen/) 对象绘制的虚线样式。 |
| [DataRecoveryMode](./datarecoverymode/) | 数据恢复模式。 |
| [DitheringMethod](./ditheringmethod/) | 抖动方法。 |
| [DitheringMethods](./ditheringmethods/) | 用于控制颜色转换的抖动方法。 |
| [FileFormat](./fileformat/) | 受支持的 PSD 文件格式之一。 |
| [FillMode](./fillmode/) | 指定闭合路径内部的填充方式。 |
| [FontStyle](./fontstyle/) | 指定应用于文本的样式信息。 |
| [GraphicsUnit](./graphicsunit/) | 指定给定数据的计量单位。 |
| [HatchStyle](./hatchstyle/) | 指定 [`HatchBrush`](../aspose.psd.brushes/hatchbrush/) 对象可用的不同图案。 |
| [HotkeyPrefix](./hotkeyprefix/) | 指定与文本相关的快捷键前缀的显示类型。 |
| [ImageFilterType](./imagefiltertype/) | 要使用的图像过滤器 |
| [InterpolationMode](./interpolationmode/) | [`InterpolationMode`](../aspose.psd/interpolationmode/) 枚举指定在对图像进行缩放或旋转时使用的算法。 |
| [KnownColor](./knowncolor/) | 指定已知的系统颜色。 |
| [LineCap](./linecap/) | 指定 [`Pen`](../aspose.psd/pen/) 对象可以用于线段结束的可用帽子样式。 |
| [LineJoin](./linejoin/) | 指定如何连接包含在 [`GraphicsPath`](../aspose.psd/graphicspath/) 对象中的图形（子路径）中的连续直线或曲线段。 |
| [MatrixOrder](./matrixorder/) | 指定矩阵变换操作的顺序。 |
| [PdfComplianceVersion](./pdfcomplianceversion/) | 指定输出文件的 PDF 合规级别。 |
| [PenAlignment](./penalignment/) | 指定[`Pen`](../aspose.psd/pen/)对象相对于理论零宽线的对齐方式。 |
| [PenType](./pentype/) | 指定[`Pen`](../aspose.psd/pen/)对象用于填充线条的填充类型。 |
| [PixelFormat](./pixelformat/) | 像素数据格式的实际含义。 |
| [ResizeType](./resizetype/) | 指定调整大小的类型。 |
| [ResolutionUnit](./resolutionunit/) | 分辨率单位枚举。 |
| [RotateFlipType](./rotatefliptype/) | 指定图像旋转的角度以及用于翻转图像的轴。 |
| [SeekOrigin](./seekorigin/) | 提供表示[`StreamContainer`](../aspose.psd/streamcontainer/)中参考点的字段，以便进行定位。 |
| [SmoothingMode](./smoothingmode/) | 指定是否对线条、曲线以及填充区域的边缘应用平滑（抗锯齿）。 |
| [StringAlignment](./stringalignment/) | 指定文本字符串相对于其布局矩形的对齐方式。 |
| [StringDigitSubstitute](./stringdigitsubstitute/) | 此枚举指定如何根据用户的地区或语言替换字符串中的数字。 |
| [StringFormatFlags](./stringformatflags/) | 指定文本字符串的显示和布局信息。 |
| [StringTrimming](./stringtrimming/) | 指定如何裁剪无法完全适配布局形状的字符串中的字符。 |
| [TextRenderingHint](./textrenderinghint/) | 指定文本渲染的质量。 |
| [WarpMode](./warpmode/) | 指定所应用的扭曲变换类型。 |
| [WrapMode](./wrapmode/) | 指定当纹理或渐变小于填充区域时的平铺方式。 |


