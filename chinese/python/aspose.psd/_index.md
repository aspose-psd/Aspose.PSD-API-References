---
title: "aspose.psd"
type: docs
weight: 10
url: /zh/python-net/aspose.psd/
---


该模块是嵌套模块的核心，也是用于 Aspose.PSD 处理的最基本对象。

## **Classes**
| **类** | **Description** |
| :- | :- |
| [Blend](/psd/python-net/aspose.psd/blend/) | 定义混合模式。此类不可继承。 |
| [Brush](/psd/python-net/aspose.psd/brush/) | 基刷类。 |
| [BuildVersionInfo](/psd/python-net/aspose.psd/buildversioninfo/) | 包含当前构建版本信息。 |
| [Cache](/psd/python-net/aspose.psd/cache/) | 包含缓存设置。 |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) | 像素的 CMYK 颜色。 |
| [CmykColorHelper](/psd/python-net/aspose.psd/cmykcolorhelper/) | 帮助方法用于处理以有符号 32 位整数表示的 CMYK 颜色。<br/>            提供与 [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) 结构体类似的 API。<br/>            它更轻量，因为 CMYK 颜色仅以 Int32 表示，而不是具有内部字段的结构体。<br/>            请在可能的情况下优先使用此类的静态方法，而不是已弃用的<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) 结构体。 |
| [Color](/psd/python-net/aspose.psd/color/) | 像素的颜色。 |
| [ColorBlend](/psd/python-net/aspose.psd/colorblend/) | 定义用于在多色渐变中插值颜色混合的颜色和位置数组。此类不可被继承。 |
| [ColorMap](/psd/python-net/aspose.psd/colormap/) | 定义颜色转换映射。[ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) 类的多个方法通过使用颜色重新映射表（即 [ColorMap](/psd/python-net/aspose.psd/colormap/) 结构体数组）来调整图像颜色。不可继承。 |
| [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) | 定义一个 5×5 矩阵，包含 RGBA 空间的坐标。[ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) 类的多个方法通过使用颜色矩阵来调整图像颜色。此类不可被继承。 |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) | 定义组成调色板的颜色数组。颜色为 32 位 ARGB 颜色。不可继承。 |
| [ColorPaletteHelper](/psd/python-net/aspose.psd/colorpalettehelper/) | 用于调色板操作的帮助类。 |
| [ColorTranslator](/psd/python-net/aspose.psd/colortranslator/) | 在 GDI+ Color 结构体之间转换颜色。此类不可被继承。 |
| [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) | 封装自定义用户定义的线帽。 |
| [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/) | 数据流容器。 |
| [DisposableObject](/psd/python-net/aspose.psd/disposableobject/) | 表示可释放的对象。 |
| [Figure](/psd/python-net/aspose.psd/figure/) | 图形。形状的容器。 |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer/) | 用于文件流处理的帮助类。 |
| [Font](/psd/python-net/aspose.psd/font/) | 定义文本的特定格式，包括字体、大小和样式属性。此类不可被继承。 |
| [FontSettings](/psd/python-net/aspose.psd/fontsettings/) | 通用 PSD 矢量格式渲染器的字体设置。 |
| [Graphics](/psd/python-net/aspose.psd/graphics/) | 根据当前程序集使用的图形引擎表示图形。 |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) | 表示一系列相连的直线和曲线。此类不可被继承。 |
| [IAdvancedBufferProcessor](/psd/python-net/aspose.psd/iadvancedbufferprocessor/) | 高级缓冲区处理器。 |
| [IBufferProcessor](/psd/python-net/aspose.psd/ibufferprocessor/) | 缓冲区处理器。 |
| [IColorConverter](/psd/python-net/aspose.psd/icolorconverter/) | 颜色转换器。 |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette/) | 调色板接口。 |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator/) | 图像创建器。 |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor/) | 图像创建器描述符，指定创建器属性。创建器描述符用于克服<br/>            必须在内存中保留每个图像创建器实例以及多线程问题的需求。 |
| [IImageDescriptor](/psd/python-net/aspose.psd/iimagedescriptor/) | 图像描述符。包含所有其他图像描述符类型的基础属性和方法。 |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter/) | 图像导出器。可以将内部 Aspose.PSD 格式的数据导出为指定的数据格式。 |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor/) | 表示图像导出器描述符。导出器描述符用于克服必须在内存中保留每个导出器实例<br/>            以及多线程问题的需求。 |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader/) | 图像加载器。 |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor/) | 图像加载器描述符，指定加载器属性。加载器描述符用于克服<br/>            必须在内存中保留每个图像加载器实例以及多线程问题的需求。 |
| [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter/) | 用于索引图像格式的颜色转换器。 |
| [IKeyedObject](/psd/python-net/aspose.psd/ikeyedobject/) | 表示具有键的对象的接口。 |
| [IObjectWithBounds](/psd/python-net/aspose.psd/iobjectwithbounds/) | 表示具有边界的对象。 |
| [IOrderedShape](/psd/python-net/aspose.psd/iorderedshape/) | 表示有序形状。有序形状是一组连续的点，具有起始点和结束点。<br/>            使用特定规则连接的连续点集合。 |
| [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader/) | 符合部分加载的 32 位 ARGB 像素。 |
| [IPartialArgb64PixelLoader](/psd/python-net/aspose.psd/ipartialargb64pixelloader/) | 64 位 ARGB 像素加载器。 |
| [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader/) | 符合部分加载的像素。 |
| [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader/) | 部分数据加载器。 |
| [IPsdColorPalette](/psd/python-net/aspose.psd/ipsdcolorpalette/) | pasd 颜色调色板 |
| [IRasterImageArgb32PixelLoader](/psd/python-net/aspose.psd/irasterimageargb32pixelloader/) | 光栅图像 32 位 ARGB 像素加载器。 |
| [IRasterImagePixelLoader](/psd/python-net/aspose.psd/irasterimagepixelloader/) | 光栅图像像素加载器。 |
| [IRasterImageRawDataLoader](/psd/python-net/aspose.psd/irasterimagerawdataloader/) | 光栅图像原始数据加载器。 |
| [Image](/psd/python-net/aspose.psd/image/) | 图像是所有类型图像的基类。 |
| [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) | 一个 [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) 对象包含有关在渲染过程中如何操作位图和元文件颜色的信息。一个 [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) 对象维护多个颜色调整设置，包括颜色调整矩阵、灰度调整矩阵、伽马校正值、颜色映射表和颜色阈值。在渲染期间，颜色可以被校正、变暗、变亮和移除。要应用这些操作，请初始化一个 [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) 对象，并将该 [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) 对象的路径（以及一个 [Image](/psd/python-net/aspose.psd/image/) 对象的路径）传递给 DrawImage 方法。 |
| [ImageCreatorsRegistry](/psd/python-net/aspose.psd/imagecreatorsregistry/) | 表示图像创建器注册表。 |
| [ImageExportersRegistry](/psd/python-net/aspose.psd/imageexportersregistry/) | 表示图像导出器注册表。 |
| [ImageLoadersRegistry](/psd/python-net/aspose.psd/imageloadersregistry/) | 表示图像加载器注册表。 |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase/) | 图像基础选项。 |
| [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings/) | 图像大小调整设置类 |
| [IntRange](/psd/python-net/aspose.psd/intrange/) | 用于表示元素序列的类 |
| [License](/psd/python-net/aspose.psd/license/) | 提供对组件授权的方法。 |
| [LoadOptions](/psd/python-net/aspose.psd/loadoptions/) | 表示加载选项。 |
| [Matrix](/psd/python-net/aspose.psd/matrix/) | 替代 GDI+ 矩阵。 |
| [Metered](/psd/python-net/aspose.psd/metered/) | 提供设置计量密钥的方法。 |
| [NonGenericDictionary](/psd/python-net/aspose.psd/nongenericdictionary/) | 表示非泛型字典。 |
| [NonGenericList](/psd/python-net/aspose.psd/nongenericlist/) | 非泛型对象列表 |
| [ObjectWithBounds](/psd/python-net/aspose.psd/objectwithbounds/) | 具有边界的对象。 |
| [OpenTypeFontsCache](/psd/python-net/aspose.psd/opentypefontscache/) | 系统中已安装的 OpenType 字体缓存。 |
| [Pen](/psd/python-net/aspose.psd/pen/) | 定义用于绘制线条、曲线和图形的对象。 |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) | 像素数据格式。这是一个不可变对象。 |
| [PixelsData](/psd/python-net/aspose.psd/pixelsdata/) | 用于存储图像像素数据及其边界的类。 |
| [PluginLicenseException](/psd/python-net/aspose.psd/pluginlicenseexception/) | 插件许可证异常 |
| [Point](/psd/python-net/aspose.psd/point/) | 表示整数 x 和 y 坐标的有序对，定义二维平面上的一点。 |
| [PointF](/psd/python-net/aspose.psd/pointf/) | 表示浮点数 x 和 y 坐标的有序对，定义二维平面上的一点。 |
| [RasterCachedImage](/psd/python-net/aspose.psd/rastercachedimage/) | 表示支持光栅图形操作的光栅图像。需要时此图像会缓存像素数据。 |
| [RasterImage](/psd/python-net/aspose.psd/rasterimage/) | 表示支持光栅图形操作的光栅图像。 |
| [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings/) | 原始数据设置 |
| [Rectangle](/psd/python-net/aspose.psd/rectangle/) | 存储表示矩形位置和大小的四个整数。 |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef/) | 存储表示矩形位置和大小的四个浮点数。 |
| [Region](/psd/python-net/aspose.psd/region/) | 描述由矩形和路径组成的图形形状的内部。此类不可继承。 |
| [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting/) | 图像保存选项的分辨率设置。 |
| [Shape](/psd/python-net/aspose.psd/shape/) | 形状。使用特定规则连接的连续点集合。 |
| [ShapeSegment](/psd/python-net/aspose.psd/shapesegment/) | 表示形状段。段是连接两个点的直线或曲线。 |
| [Size](/psd/python-net/aspose.psd/size/) | 表示尺寸。 |
| [SizeF](/psd/python-net/aspose.psd/sizef/) | 存储一对有序的浮点数，通常表示矩形的宽度和高度。 |
| [Source](/psd/python-net/aspose.psd/source/) | 源用于包含对象管道的所有相关信息。 |
| [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) | 表示分割流容器，包含流并提供流处理例程。 |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) | 表示流容器，包含流并提供流处理例程。 |
| [StringFormat](/psd/python-net/aspose.psd/stringformat/) | 封装文本布局信息（如对齐、方向和制表位）、显示操作（如省略号插入和数字本地化替换）以及 OpenType 功能。此类不可被继承。 |
| [TransparencySupporter](/psd/python-net/aspose.psd/transparencysupporter/) | 支持透明度的对象。 |
| [VectorImage](/psd/python-net/aspose.psd/vectorimage/) | 矢量图像是所有矢量图像类型的基类。 |
## **Enumerations**
| **Enumeration** | **Description** |
| :- | :- |
| [CacheType](/psd/python-net/aspose.psd/cachetype/) | 指定要使用的缓存类型。 |
| [CharacterSet](/psd/python-net/aspose.psd/characterset/) | 表示使用的字符集。 |
| [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) | 指定哪些对象使用颜色调整信息。 |
| [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) | 指定 CMYK（青色、品红、黄色、黑色）颜色空间中的各个通道。此枚举由 SetOutputChannel 方法使用。 |
| [ColorCompareMethod](/psd/python-net/aspose.psd/colorcomparemethod/) | 用于调整到最近邻的颜色比较方法 |
| [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) | 指定受 [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) 的颜色和灰度调整设置影响的图像和颜色类型。 |
| [ColorQuantizationMethod](/psd/python-net/aspose.psd/colorquantizationmethod/) | 颜色量化方法 |
| [CompositingQuality](/psd/python-net/aspose.psd/compositingquality/) | 指定合成过程中使用的质量级别。 |
| [DashCap](/psd/python-net/aspose.psd/dashcap/) | 指定虚线中每段破折号两端使用的图形形状类型。 |
| [DashStyle](/psd/python-net/aspose.psd/dashstyle/) | 指定使用 [Pen](/psd/python-net/aspose.psd/pen/) 对象绘制的虚线样式。 |
| [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode/) | 数据恢复模式。 |
| [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod/) | 抖动方法。 |
| [DitheringMethods](/psd/python-net/aspose.psd/ditheringmethods/) | 用于控制颜色转换的抖动方法。 |
| [FileFormat](/psd/python-net/aspose.psd/fileformat/) | 受支持的 PSD 文件格式之一。 |
| [FillMode](/psd/python-net/aspose.psd/fillmode/) | 指定封闭路径内部的填充方式。 |
| [FontStyle](/psd/python-net/aspose.psd/fontstyle/) | 指定应用于文本的样式信息。 |
| [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) | 指定给定数据的计量单位。 |
| [HatchStyle](/psd/python-net/aspose.psd/hatchstyle/) | 指定 [HatchBrush](/psd/python-net/aspose.psd.brushes/hatchbrush/) 对象可用的不同图案。 |
| [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) | 指定与文本相关的快捷键前缀的显示类型。 |
| [ImageFilterType](/psd/python-net/aspose.psd/imagefiltertype/) | 要使用的图像过滤器 |
| [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) | 枚举 [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) 指定在对图像进行缩放或旋转时使用的算法。 |
| [KnownColor](/psd/python-net/aspose.psd/knowncolor/) | 指定已知的系统颜色。 |
| [LineCap](/psd/python-net/aspose.psd/linecap/) | 指定 [Pen](/psd/python-net/aspose.psd/pen/) 对象可以用于线段结束的可用帽式样。 |
| [LineJoin](/psd/python-net/aspose.psd/linejoin/) | 指定如何在 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 对象中包含的图形（子路径）里连接连续的直线或曲线段。 |
| [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) | 指定矩阵变换操作的顺序。 |
| [PdfComplianceVersion](/psd/python-net/aspose.psd/pdfcomplianceversion/) | 指定输出文件的 PDF 合规级别。 |
| [PenAlignment](/psd/python-net/aspose.psd/penalignment/) | 指定 [Pen](/psd/python-net/aspose.psd/pen/) 对象相对于理论的零宽线的对齐方式。 |
| [PenType](/psd/python-net/aspose.psd/pentype/) | 指定 [Pen](/psd/python-net/aspose.psd/pen/) 对象用于填充线条的填充类型。 |
| [PixelFormat](/psd/python-net/aspose.psd/pixelformat/) | 像素数据格式的实际含义。 |
| [ResizeType](/psd/python-net/aspose.psd/resizetype/) | 指定调整大小的类型。 |
| [ResolutionUnit](/psd/python-net/aspose.psd/resolutionunit/) | 分辨率单位枚举。 |
| [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype/) | 指定图像旋转的角度以及用于翻转图像的轴。 |
| [SeekOrigin](/psd/python-net/aspose.psd/seekorigin/) | 提供在 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) 中用于定位的参考点字段。 |
| [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode/) | 指定是否对线条、曲线以及填充区域的边缘应用平滑（抗锯齿）。 |
| [StringAlignment](/psd/python-net/aspose.psd/stringalignment/) | 指定文本字符串相对于其布局矩形的对齐方式。 |
| [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute/) | 枚举指定如何根据用户的地区或语言替换字符串中的数字。 |
| [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) | 指定文本字符串的显示和布局信息。 |
| [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) | 指定如何从无法完全适配布局形状的字符串中修剪字符。 |
| [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint/) | 指定文本渲染的质量。 |
| [WarpMode](/psd/python-net/aspose.psd/warpmode/) | 指定所应用的扭曲变换类型。 |
| [WrapMode](/psd/python-net/aspose.psd/wrapmode/) | 指定当纹理或渐变小于填充区域时的平铺方式。 |
