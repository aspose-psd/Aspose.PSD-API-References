---
title: "Aspose.PSD"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "El espacio de nombres es el núcleo de los espacios de nombres anidados y los objetos más básicos utilizados para el procesamiento de Aspose.PSD."
type: docs
weight: 10
url: /es/net/aspose.psd/
---
{{< psd/tize >}}
El espacio de nombres es el núcleo para los espacios de nombres anidados y los objetos más básicos utilizados para el procesamiento de Aspose.PSD.

## Clases

| Clase | Descripción |
| --- | --- |
| [AggregateException](./aggregateexception/) | Agrupa múltiples excepciones. |
| [Blend](./blend/) | Define un patrón de mezcla. Esta clase no puede heredarse. |
| [Brush](./brush/) | La clase base de pincel. |
| [BuildVersionInfo](./buildversioninfo/) | Contiene la información de la versión de compilación actual. |
| [Cache](./cache/) | Contiene la configuración de caché. |
| [CmykColorHelper](./cmykcolorhelper/) | Métodos auxiliares para trabajar con colores CMYK presentados como un valor entero de 32 bits con signo. Proporciona una API similar a la estructura [`CmykColor`](../aspose.psd/cmykcolor/). Es más ligera porque el color CMYK se presenta simplemente como Int32 en lugar de una estructura con campos internos. Por favor, prefiera usar los métodos estáticos de esta clase cuando sea posible en lugar de la estructura [`CmykColor`](../aspose.psd/cmykcolor/) obsoleta. |
| [ColorBlend](./colorblend/) | Define matrices de colores y posiciones utilizadas para interpolar la mezcla de colores en un degradado multicolor. Esta clase no puede heredarse. |
| [ColorMap](./colormap/) | Define un mapa para convertir colores. Varios métodos de la clase [`ImageAttributes`](../aspose.psd/imageattributes/) ajustan los colores de la imagen mediante una tabla de remapeo de colores, que es una matriz de estructuras [`ColorMap`](../aspose.psd/colormap/). No heredable. |
| [ColorMatrix](./colormatrix/) | Define una matriz de 5 x 5 que contiene las coordenadas para el espacio RGBA. Varios métodos de la clase [`ImageAttributes`](../aspose.psd/imageattributes/) ajustan los colores de la imagen mediante una matriz de colores. Esta clase no puede heredarse. |
| [ColorPalette](./colorpalette/) | Define una matriz de colores que forman una paleta de colores. Los colores son colores ARGB de 32 bits. No heredable. |
| [ColorPaletteHelper](./colorpalettehelper/) | Clase auxiliar para la manipulación de paletas de colores. |
| [ColorTranslator](./colortranslator/) | Traduce colores hacia y desde estructuras GDI+ Color. Esta clase no puede heredarse. |
| [CompositeException](./compositeexception/) | La excepción compuesta |
| [CustomLineCap](./customlinecap/) | Encapsula una tapa de línea personalizada definida por el usuario. |
| [DataStreamSupporter](./datastreamsupporter/) | El contenedor de flujo de datos. |
| [DisposableObject](./disposableobject/) | Representa un objeto desechable. |
| [Figure](./figure/) | La figura. Un contenedor para formas. |
| [FileStreamContainer](./filestreamcontainer/) | Ayudante para el procesamiento de flujos de archivo. |
| [Font](./font/) | Define un formato particular para texto, incluyendo la tipografía, el tamaño y los atributos de estilo. Esta clase no puede heredarse. |
| [FontSettings](./fontsettings/) | Configuración de fuentes del renderizador de formatos vectoriales PSD generales. |
| [Graphics](./graphics/) | Representa los gráficos según el motor gráfico usado en el ensamblado actual. |
| [GraphicsPath](./graphicspath/) | Representa una serie de líneas y curvas conectadas. Esta clase no puede heredarse. |
| [Image](./image/) | La imagen es la clase base para todo tipo de imágenes. |
| [ImageAttributes](./imageattributes/) | Un objeto [`ImageAttributes`](../aspose.psd/imageattributes/) contiene información sobre cómo se manipulan los colores de mapas de bits y metafiles durante el renderizado. Un objeto [`ImageAttributes`](../aspose.psd/imageattributes/) mantiene varios ajustes de color, incluyendo matrices de ajuste de color, matrices de ajuste de escala de grises, valores de corrección gamma, tablas de mapeo de colores y valores de umbral de color. Durante el renderizado, los colores pueden corregirse, oscurecerse, aclararse y eliminarse. Para aplicar dichas manipulaciones, inicialice un objeto [`ImageAttributes`](../aspose.psd/imageattributes/) y pase la ruta de ese objeto [`ImageAttributes`](../aspose.psd/imageattributes/) (junto con la ruta de un [`Image`](../aspose.psd/image/)) al método DrawImage. |
| [ImageCreatorsRegistry](./imagecreatorsregistry/) | Representa el registro de creadores de imágenes. |
| [ImageExportersRegistry](./imageexportersregistry/) | Representa el registro de exportadores de imágenes. |
| [ImageLoadersRegistry](./imageloadersregistry/) | Representa el registro de cargadores de imágenes. |
| [ImageOptionsBase](./imageoptionsbase/) | Las opciones base de la imagen. |
| [ImageResizeSettings](./imageresizesettings/) | Clase de configuración de redimensionamiento de imagen |
| [IntRange](./intrange/) | Clase para representar una secuencia de elementos |
| [License](./license/) | Proporciona métodos para licenciar el componente. |
| [LoadOptions](./loadoptions/) | Representa las opciones de carga. |
| [Matrix](./matrix/) | Reemplaza la matriz GDI+. |
| [Metered](./metered/) | Proporciona métodos para establecer la clave medida. |
| [NonGenericDictionary](./nongenericdictionary/) | Representa un diccionario no genérico. |
| [NonGenericList](./nongenericlist/) | Lista no genérica de objetos |
| [ObjectWithBounds](./objectwithbounds/) | El objeto que tiene límites. |
| [OpenTypeFontsCache](./opentypefontscache/) | Caché para fuentes OpenType que están instaladas en el sistema. |
| [Pen](./pen/) | Define un objeto usado para dibujar líneas, curvas y figuras. |
| [PixelDataFormat](./pixeldataformat/) | El formato de datos de píxel. Este es un objeto inmutable. |
| [PixelsData](./pixelsdata/) | La clase para almacenar los datos de píxeles de la imagen y sus límites. |
| [PluginLicenseException](./pluginlicenseexception/) | Excepción para licencia del complemento |
| [ProgressEventHandler](./progresseventhandler/) | Referencia a la función manejadora del evento de progreso |
| [RasterCachedImage](./rastercachedimage/) | Representa una imagen raster que soporta operaciones gráficas raster. Esta imagen almacena en caché los datos de píxel cuando se requiere. |
| [RasterImage](./rasterimage/) | Representa una imagen raster que soporta operaciones gráficas raster. |
| [RawDataSettings](./rawdatasettings/) | La configuración de datos sin procesar |
| [Region](./region/) | Describe el interior de una forma gráfica compuesta de rectángulos y rutas. Esta clase no puede heredarse. |
| [ResolutionSetting](./resolutionsetting/) | La configuración de resolución para las opciones de guardado de imagen. |
| [Shape](./shape/) | La forma. Un conjunto continuo de puntos conectados mediante una regla específica. |
| [ShapeSegment](./shapesegment/) | Representa un segmento de forma. Un segmento es una línea o curva que conecta dos puntos. |
| [Source](./source/) | La fuente se usa para contener toda la información relevante para una tubería de objeto. |
| [SplitStreamContainer](./splitstreamcontainer/) | Representa un contenedor de flujo dividido que contiene el flujo y proporciona rutinas de procesamiento de flujo. |
| [StreamContainer](./streamcontainer/) | Representa un contenedor de flujo que contiene el flujo y proporciona rutinas de procesamiento de flujo. |
| [StringFormat](./stringformat/) | Encapsula información de diseño de texto (como alineación, orientación y tabulaciones) manipulaciones de visualización (como inserción de elipsis y sustitución de dígitos nacionales) y características OpenType. Esta clase no puede heredarse. |
| [TransparencySupporter](./transparencysupporter/) | El objeto que soporta transparencia. |
| [VectorImage](./vectorimage/) | La imagen vectorial es la clase base para todo tipo de imágenes vectoriales. |
## Structures

| Estructura | Descripción |
| --- | --- |
| [CmykColor](./cmykcolor/) | El color CMYK del píxel. |
| [Color](./color/) | El color del píxel. |
| [Point](./point/) | Representa un par ordenado de coordenadas enteras x e y que define un punto en un plano bidimensional. |
| [PointF](./pointf/) | Representa un par ordenado de coordenadas de punto flotante x e y que define un punto en un plano bidimensional. |
| [Rectangle](./rectangle/) | Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo. |
| [RectangleF](./rectanglef/) | Almacena un conjunto de cuatro números de punto flotante que representan la ubicación y el tamaño de un rectángulo. |
| [Size](./size/) | Representa el tamaño. |
| [SizeF](./sizef/) | Almacena un par ordenado de números de punto flotante, típicamente el ancho y la altura de un rectángulo. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IAdvancedBufferProcessor](./iadvancedbufferprocessor/) | El procesador avanzado de búfer. |
| [IBufferProcessor](./ibufferprocessor/) | El procesador de búfer. |
| [IColorConverter](./icolorconverter/) | El convertidor de color. |
| [IColorPalette](./icolorpalette/) | La interfaz de paleta de colores. |
| [IImageCreator](./iimagecreator/) | El creador de imágenes. |
| [IImageCreatorDescriptor](./iimagecreatordescriptor/) | El descriptor del creador de imágenes que especifica las propiedades del creador. El descriptor del creador se usa para superar la necesidad de contener cada instancia del creador de imágenes en memoria y los problemas de multihilo. |
| [IImageDescriptor](./iimagedescriptor/) | El descriptor de imagen. Contiene propiedades y métodos base para todos los demás tipos de descriptor de imagen. |
| [IImageExporter](./iimageexporter/) | El exportador de imágenes. Puede exportar datos del formato interno Aspose.PSD a un formato de datos especificado. |
| [IImageExporterDescriptor](./iimageexporterdescriptor/) | Representa el descriptor del exportador de imágenes. El descriptor del exportador se usa para superar la necesidad de contener cada instancia del exportador en memoria y los problemas de multihilo. |
| [IImageLoader](./iimageloader/) | El cargador de imágenes. |
| [IImageLoaderDescriptor](./iimageloaderdescriptor/) | El descriptor del cargador de imágenes que especifica las propiedades del cargador. El descriptor del cargador se usa para superar la necesidad de contener cada instancia del cargador de imágenes en memoria y los problemas de multihilo. |
| [IIndexedColorConverter](./iindexedcolorconverter/) | El convertidor de color para formatos de imagen indexados. |
| [IKeyedObject](./ikeyedobject/) | Representa la interfaz para objetos con claves. |
| [IObjectWithBounds](./iobjectwithbounds/) | Representa un objeto con límites. |
| [IOrderedShape](./iorderedshape/) | Representa una forma ordenada. Una forma ordenada es un conjunto continuo de puntos que tiene un punto de inicio y un punto final. El conjunto continuo de puntos está conectado usando una regla específica. |
| [IPartialArgb32PixelLoader](./ipartialargb32pixelloader/) | Cumple con los píxeles ARGB de 32 bits cargados parcialmente. |
| [IPartialArgb64PixelLoader](./ipartialargb64pixelloader/) | El cargador de píxeles ARGB de 64 bits. |
| [IPartialPixelLoader](./ipartialpixelloader/) | Cumple con los píxeles cargados parcialmente. |
| [IPartialRawDataLoader](./ipartialrawdataloader/) | El cargador de datos parciales. |
| [IPsdColorPalette](./ipsdcolorpalette/) | La paleta de colores pasd |
| [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader/) | El cargador de píxeles ARGB de 32 bits de imagen raster. |
| [IRasterImagePixelLoader](./irasterimagepixelloader/) | El cargador de píxeles de imagen raster. |
| [IRasterImageRawDataLoader](./irasterimagerawdataloader/) | El cargador de datos sin procesar de la imagen raster. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [CacheType](./cachetype/) | Especifica el tipo de caché a usar. |
| [CharacterSet](./characterset/) | Representa el conjunto de caracteres usado. |
| [ColorAdjustType](./coloradjusttype/) | Especifica qué objetos usan información de ajuste de color. |
| [ColorChannelFlag](./colorchannelflag/) | Especifica los canales individuales en el espacio de color CMYK (cian, magenta, amarillo, negro). Esta enumeración es utilizada por los métodos SetOutputChannel. |
| [ColorCompareMethod](./colorcomparemethod/) | Método de comparación de color para ajustar al vecino más cercano |
| [ColorMatrixFlag](./colormatrixflag/) | Especifica los tipos de imágenes y colores que se verán afectados por la configuración de ajuste de color y escala de grises de un [`ImageAttributes`](../aspose.psd/imageattributes/). |
| [ColorQuantizationMethod](./colorquantizationmethod/) | Métodos de cuantización de colores |
| [CompositingQuality](./compositingquality/) | Especifica el nivel de calidad a usar durante la composición. |
| [DashCap](./dashcap/) | Especifica el tipo de forma gráfica a usar en ambos extremos de cada guión en una línea discontinua. |
| [DashStyle](./dashstyle/) | Especifica el estilo de líneas discontinuas dibujadas con un objeto [`Pen`](../aspose.psd/pen/). |
| [DataRecoveryMode](./datarecoverymode/) | El modo de recuperación de datos. |
| [DitheringMethod](./ditheringmethod/) | Método de tramado. |
| [DitheringMethods](./ditheringmethods/) | Los métodos de tramado utilizados para controlar la conversión de color. |
| [FileFormat](./fileformat/) | Uno de los formatos de archivo PSD compatibles. |
| [FillMode](./fillmode/) | Especifica cómo se rellena el interior de una ruta cerrada. |
| [FontStyle](./fontstyle/) | Especifica la información de estilo aplicada al texto. |
| [GraphicsUnit](./graphicsunit/) | Especifica la unidad de medida para los datos proporcionados. |
| [HatchStyle](./hatchstyle/) | Especifica los diferentes patrones disponibles para objetos [`HatchBrush`](../aspose.psd.brushes/hatchbrush/). |
| [HotkeyPrefix](./hotkeyprefix/) | Especifica el tipo de visualización para los prefijos de teclas rápidas que se relacionan con el texto. |
| [ImageFilterType](./imagefiltertype/) | Filtros de imagen a usar |
| [InterpolationMode](./interpolationmode/) | La enumeración [`InterpolationMode`](../aspose.psd/interpolationmode/) especifica el algoritmo que se utiliza cuando las imágenes se escalan o rotan. |
| [KnownColor](./knowncolor/) | Especifica los colores del sistema conocidos. |
| [LineCap](./linecap/) | Especifica los estilos de extremo disponibles con los que un objeto [`Pen`](../aspose.psd/pen/) puede terminar una línea. |
| [LineJoin](./linejoin/) | Especifica cómo unir segmentos consecutivos de línea o curva en una figura (subruta) contenida en un objeto [`GraphicsPath`](../aspose.psd/graphicspath/). |
| [MatrixOrder](./matrixorder/) | Especifica el orden de las operaciones de transformación de matrices. |
| [PdfComplianceVersion](./pdfcomplianceversion/) | Especifica el nivel de cumplimiento PDF del archivo de salida. |
| [PenAlignment](./penalignment/) | Especifica la alineación de un objeto [`Pen`](../aspose.psd/pen/) en relación con la línea teórica de ancho cero. |
| [PenType](./pentype/) | Especifica el tipo de relleno que un objeto [`Pen`](../aspose.psd/pen/) utiliza para rellenar líneas. |
| [PixelFormat](./pixelformat/) | El significado real del formato de datos de píxel. |
| [ResizeType](./resizetype/) | Especifica el tipo de redimensionamiento. |
| [ResolutionUnit](./resolutionunit/) | Enumeración de unidad de resolución. |
| [RotateFlipType](./rotatefliptype/) | Especifica cuánto se rota una imagen y el eje utilizado para voltearla. |
| [SeekOrigin](./seekorigin/) | Proporciona los campos que representan puntos de referencia en [`StreamContainer`](../aspose.psd/streamcontainer/) para la búsqueda. |
| [SmoothingMode](./smoothingmode/) | Especifica si se aplica suavizado (antialiasing) a líneas y curvas y a los bordes de áreas rellenas. |
| [StringAlignment](./stringalignment/) | Especifica la alineación de una cadena de texto respecto a su rectángulo de diseño. |
| [StringDigitSubstitute](./stringdigitsubstitute/) | La enumeración especifica cómo sustituir dígitos en una cadena según la configuración regional o el idioma del usuario. |
| [StringFormatFlags](./stringformatflags/) | Especifica la información de visualización y diseño para cadenas de texto. |
| [StringTrimming](./stringtrimming/) | Especifica cómo recortar caracteres de una cadena que no cabe completamente en una forma de diseño. |
| [TextRenderingHint](./textrenderinghint/) | Especifica la calidad del renderizado de texto. |
| [WarpMode](./warpmode/) | Especifica el tipo de transformación de deformación aplicada. |
| [WrapMode](./wrapmode/) | Especifica cómo se mosaica una textura o degradado cuando es más pequeña que el área a rellenar. |


