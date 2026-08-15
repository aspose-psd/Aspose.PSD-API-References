---
title: "aspose.psd"
type: docs
weight: 10
url: /es/python-net/aspose.psd/
---


El módulo es el núcleo para módulos anidados y los objetos más básicos utilizados para el procesamiento de Aspose.PSD.

## **Classes**
| **Class** | **Descripción** |
| :- | :- |
| [Blend](/psd/python-net/aspose.psd/blend/) | Define un patrón de mezcla. Esta clase no puede ser heredada. |
| [Brush](/psd/python-net/aspose.psd/brush/) | La clase base de pincel. |
| [BuildVersionInfo](/psd/python-net/aspose.psd/buildversioninfo/) | Contiene la información de la versión de compilación actual. |
| [Cache](/psd/python-net/aspose.psd/cache/) | Contiene la configuración de caché. |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) | El color CMYK del píxel. |
| [CmykColorHelper](/psd/python-net/aspose.psd/cmykcolorhelper/) | Métodos auxiliares para trabajar con el color CMYK presentado como un entero con signo de 32 bits.<br/>            Proporciona una API similar a la estructura [CmykColor](/psd/python-net/aspose.psd/cmykcolor/).<br/>            Es más liviano porque el color CMYK se presenta simplemente como Int32 en lugar de una estructura con campos internos.<br/>            Por favor, prefiera usar los métodos estáticos de esta clase cuando sea posible en lugar del obsoleto<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) estructura. |
| [Color](/psd/python-net/aspose.psd/color/) | El color del píxel. |
| [ColorBlend](/psd/python-net/aspose.psd/colorblend/) | Define matrices de colores y posiciones usadas para interpolar la mezcla de colores en un degradado multicolor. Esta clase no puede heredarse. |
| [ColorMap](/psd/python-net/aspose.psd/colormap/) | Define un mapa para convertir colores. Varios métodos de la clase [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) ajustan los colores de la imagen usando una tabla de remapeo de colores, que es una matriz de estructuras [ColorMap](/psd/python-net/aspose.psd/colormap/). No heredable. |
| [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) | Define una matriz de 5 x 5 que contiene las coordenadas para el espacio RGBA. Varios métodos de la clase [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) ajustan los colores de la imagen usando una matriz de colores. Esta clase no puede heredarse. |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) | Define una matriz de colores que forman una paleta de colores. Los colores son colores ARGB de 32 bits. No heredable. |
| [ColorPaletteHelper](/psd/python-net/aspose.psd/colorpalettehelper/) | Clase auxiliar para la manipulación de paletas de colores. |
| [ColorTranslator](/psd/python-net/aspose.psd/colortranslator/) | Traduce colores a y desde estructuras de Color de GDI+. Esta clase no puede heredarse. |
| [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) | Encapsula una terminación de línea personalizada definida por el usuario. |
| [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/) | El contenedor del flujo de datos. |
| [DisposableObject](/psd/python-net/aspose.psd/disposableobject/) | Representa un objeto desechable. |
| [Figure](/psd/python-net/aspose.psd/figure/) | La figura. Un contenedor para formas. |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer/) | Auxiliar para el procesamiento de flujos de archivos. |
| [Font](/psd/python-net/aspose.psd/font/) | Define un formato particular para texto, incluyendo la familia tipográfica, el tamaño y los atributos de estilo. Esta clase no puede heredarse. |
| [FontSettings](/psd/python-net/aspose.psd/fontsettings/) | Configuración de fuentes del renderizador de formatos vectoriales PSD generales. |
| [Graphics](/psd/python-net/aspose.psd/graphics/) | Representa los gráficos según el motor gráfico usado en el ensamblado actual. |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) | Representa una serie de líneas y curvas conectadas. Esta clase no puede heredarse. |
| [IAdvancedBufferProcessor](/psd/python-net/aspose.psd/iadvancedbufferprocessor/) | El procesador avanzado de búfer. |
| [IBufferProcessor](/psd/python-net/aspose.psd/ibufferprocessor/) | El procesador de búfer. |
| [IColorConverter](/psd/python-net/aspose.psd/icolorconverter/) | El convertidor de color. |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette/) | La interfaz de la paleta de color. |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator/) | El creador de imágenes. |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor/) | El descriptor del creador de imagen que especifica las propiedades del creador. El descriptor del creador se utiliza para superar<br/>            la necesidad de contener cada instancia del creador de imagen en memoria y problemas de multihilo. |
| [IImageDescriptor](/psd/python-net/aspose.psd/iimagedescriptor/) | El descriptor de imagen. Contiene propiedades y métodos base para todos los demás tipos de descriptor de imagen. |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter/) | El exportador de imagen. Puede exportar datos del formato interno Aspose.PSD a un formato de datos especificado. |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor/) | Representa el descriptor del exportador de imagen. El descriptor del exportador se utiliza para superar la necesidad de contener cada instancia del exportador<br/>            en memoria y problemas de multihilo. |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader/) | El cargador de imagen. |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor/) | El descriptor del cargador de imagen que especifica las propiedades del cargador. El descriptor del cargador se utiliza para superar<br/>            la necesidad de contener cada instancia del cargador de imagen en memoria y problemas de multihilo. |
| [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter/) | El convertidor de color para formatos de imagen indexados. |
| [IKeyedObject](/psd/python-net/aspose.psd/ikeyedobject/) | Representa la interfaz para objetos con claves. |
| [IObjectWithBounds](/psd/python-net/aspose.psd/iobjectwithbounds/) | Representa un objeto con límites. |
| [IOrderedShape](/psd/python-net/aspose.psd/iorderedshape/) | Representa una forma ordenada. Una forma ordenada es un conjunto continuo de puntos que tiene un punto de inicio y un punto final.<br/>            El conjunto continuo de puntos conectado mediante una regla específica. |
| [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader/) | Cumple con los píxeles ARGB de 32 bits cargados parcialmente. |
| [IPartialArgb64PixelLoader](/psd/python-net/aspose.psd/ipartialargb64pixelloader/) | El cargador de píxeles ARGB de 64 bits. |
| [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader/) | Cumple con los píxeles cargados parcialmente. |
| [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader/) | El cargador de datos parciales. |
| [IPsdColorPalette](/psd/python-net/aspose.psd/ipsdcolorpalette/) | La paleta de colores pasd |
| [IRasterImageArgb32PixelLoader](/psd/python-net/aspose.psd/irasterimageargb32pixelloader/) | El cargador de píxeles ARGB de 32 bits de imagen raster. |
| [IRasterImagePixelLoader](/psd/python-net/aspose.psd/irasterimagepixelloader/) | El cargador de píxeles de imagen raster. |
| [IRasterImageRawDataLoader](/psd/python-net/aspose.psd/irasterimagerawdataloader/) | El cargador de datos sin procesar de imagen raster. |
| [Image](/psd/python-net/aspose.psd/image/) | La imagen es la clase base para todo tipo de imágenes. |
| [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) | Un objeto [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) contiene información sobre cómo se manipulan los colores de mapas de bits y metarchivos durante el renderizado. Un objeto [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) mantiene varios ajustes de color, incluyendo matrices de ajuste de color, matrices de ajuste de escala de grises, valores de corrección gamma, tablas de asignación de colores y valores de umbral de color. Durante el renderizado, los colores pueden ser corregidos, oscurecidos, aclarados y eliminados. Para aplicar dichas manipulaciones, inicialice un objeto [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) y pase la ruta de ese objeto [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) (junto con la ruta de una [Image](/psd/python-net/aspose.psd/image/)) al método DrawImage. |
| [ImageCreatorsRegistry](/psd/python-net/aspose.psd/imagecreatorsregistry/) | Representa el registro de creadores de imagen. |
| [ImageExportersRegistry](/psd/python-net/aspose.psd/imageexportersregistry/) | Representa el registro de exportadores de imagen. |
| [ImageLoadersRegistry](/psd/python-net/aspose.psd/imageloadersregistry/) | Representa el registro de cargadores de imagen. |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase/) | Las opciones base de imagen. |
| [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings/) | Clase de configuración de redimensionamiento de imagen |
| [IntRange](/psd/python-net/aspose.psd/intrange/) | Clase para representar una secuencia de elementos |
| [License](/psd/python-net/aspose.psd/license/) | Proporciona métodos para licenciar el componente. |
| [LoadOptions](/psd/python-net/aspose.psd/loadoptions/) | Representa las opciones de carga. |
| [Matrix](/psd/python-net/aspose.psd/matrix/) | Reemplaza la matriz GDI+. |
| [Metered](/psd/python-net/aspose.psd/metered/) | Proporciona métodos para establecer la clave medida. |
| [NonGenericDictionary](/psd/python-net/aspose.psd/nongenericdictionary/) | Representa un diccionario no genérico. |
| [NonGenericList](/psd/python-net/aspose.psd/nongenericlist/) | Lista no genérica de objetos |
| [ObjectWithBounds](/psd/python-net/aspose.psd/objectwithbounds/) | El objeto que tiene límites. |
| [OpenTypeFontsCache](/psd/python-net/aspose.psd/opentypefontscache/) | Caché para fuentes OpenType instaladas en el sistema. |
| [Pen](/psd/python-net/aspose.psd/pen/) | Define un objeto usado para dibujar líneas, curvas y figuras. |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) | El formato de datos de píxeles. Este es un objeto inmutable. |
| [PixelsData](/psd/python-net/aspose.psd/pixelsdata/) | La clase para almacenar los datos de píxeles de la imagen y sus límites. |
| [PluginLicenseException](/psd/python-net/aspose.psd/pluginlicenseexception/) | Excepción para licencia de complemento |
| [Point](/psd/python-net/aspose.psd/point/) | Representa un par ordenado de coordenadas x e y enteras que define un punto en un plano bidimensional. |
| [PointF](/psd/python-net/aspose.psd/pointf/) | Representa un par ordenado de coordenadas x e y de punto flotante que define un punto en un plano bidimensional. |
| [RasterCachedImage](/psd/python-net/aspose.psd/rastercachedimage/) | Representa una imagen raster que soporta operaciones gráficas raster. Esta imagen almacena en caché los datos de píxeles cuando es necesario. |
| [RasterImage](/psd/python-net/aspose.psd/rasterimage/) | Representa una imagen raster que soporta operaciones gráficas raster. |
| [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings/) | La configuración de datos sin procesar |
| [Rectangle](/psd/python-net/aspose.psd/rectangle/) | Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo. |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef/) | Almacena un conjunto de cuatro números de punto flotante que representan la ubicación y el tamaño de un rectángulo. |
| [Region](/psd/python-net/aspose.psd/region/) | Describe el interior de una forma gráfica compuesta de rectángulos y rutas. Esta clase no puede heredarse. |
| [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting/) | La configuración de resolución para las opciones de guardado de imagen. |
| [Shape](/psd/python-net/aspose.psd/shape/) | La forma. Un conjunto continuo de puntos conectados usando una regla específica. |
| [ShapeSegment](/psd/python-net/aspose.psd/shapesegment/) | Representa un segmento de forma. Un segmento es una línea o curva que conecta dos puntos. |
| [Size](/psd/python-net/aspose.psd/size/) | Representa el tamaño. |
| [SizeF](/psd/python-net/aspose.psd/sizef/) | Almacena un par ordenado de números de punto flotante, típicamente el ancho y la altura de un rectángulo. |
| [Source](/psd/python-net/aspose.psd/source/) | La fuente se utiliza para contener toda la información relevante para una tubería de objetos. |
| [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) | Representa un contenedor de flujo dividido que contiene el flujo y proporciona rutinas de procesamiento de flujo. |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) | Representa un contenedor de flujo que contiene el flujo y proporciona rutinas de procesamiento de flujo. |
| [StringFormat](/psd/python-net/aspose.psd/stringformat/) | Encapsula información de diseño de texto (como alineación, orientación y tabulaciones) manipulaciones de visualización (como inserción de elipsis y sustitución de dígitos nacionales) y características OpenType. Esta clase no puede heredarse. |
| [TransparencySupporter](/psd/python-net/aspose.psd/transparencysupporter/) | El objeto que soporta transparencia. |
| [VectorImage](/psd/python-net/aspose.psd/vectorimage/) | La imagen vectorial es la clase base para todo tipo de imágenes vectoriales. |
## **Enumerations**
| **Enumeration** | **Descripción** |
| :- | :- |
| [CacheType](/psd/python-net/aspose.psd/cachetype/) | Especifica el tipo de caché a usar. |
| [CharacterSet](/psd/python-net/aspose.psd/characterset/) | Representa el conjunto de caracteres utilizado. |
| [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) | Especifica qué objetos usan información de ajuste de color. |
| [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) | Especifica canales individuales en el espacio de color CMYK (cian, magenta, amarillo, negro). Esta enumeración es usada por los métodos SetOutputChannel. |
| [ColorCompareMethod](/psd/python-net/aspose.psd/colorcomparemethod/) | Método de comparación de color para ajustar al vecino más cercano |
| [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) | Especifica los tipos de imágenes y colores que se verán afectados por la configuración de ajuste de color y escala de grises de un [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/). |
| [ColorQuantizationMethod](/psd/python-net/aspose.psd/colorquantizationmethod/) | Métodos de cuantización de colores |
| [CompositingQuality](/psd/python-net/aspose.psd/compositingquality/) | Especifica el nivel de calidad a usar durante la composición. |
| [DashCap](/psd/python-net/aspose.psd/dashcap/) | Especifica el tipo de forma gráfica a usar en ambos extremos de cada guión en una línea discontinua. |
| [DashStyle](/psd/python-net/aspose.psd/dashstyle/) | Especifica el estilo de líneas discontinuas dibujadas con un objeto [Pen](/psd/python-net/aspose.psd/pen/). |
| [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode/) | El modo de recuperación de datos. |
| [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod/) | Método de tramado. |
| [DitheringMethods](/psd/python-net/aspose.psd/ditheringmethods/) | Los métodos de tramado usados para controlar la conversión de color. |
| [FileFormat](/psd/python-net/aspose.psd/fileformat/) | Uno de los formatos de archivo PSD compatibles. |
| [FillMode](/psd/python-net/aspose.psd/fillmode/) | Especifica cómo se rellena el interior de una ruta cerrada. |
| [FontStyle](/psd/python-net/aspose.psd/fontstyle/) | Especifica la información de estilo aplicada al texto. |
| [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) | Especifica la unidad de medida para los datos dados. |
| [HatchStyle](/psd/python-net/aspose.psd/hatchstyle/) | Especifica los diferentes patrones disponibles para objetos [HatchBrush](/psd/python-net/aspose.psd.brushes/hatchbrush/). |
| [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) | Especifica el tipo de visualización para los prefijos de teclas rápidas que se relacionan con el texto. |
| [ImageFilterType](/psd/python-net/aspose.psd/imagefiltertype/) | Filtros de imagen a usar |
| [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) | La enumeración [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) especifica el algoritmo que se utiliza cuando las imágenes se escalan o rotan. |
| [KnownColor](/psd/python-net/aspose.psd/knowncolor/) | Especifica los colores del sistema conocidos. |
| [LineCap](/psd/python-net/aspose.psd/linecap/) | Especifica los estilos de extremo disponibles con los que un objeto [Pen](/psd/python-net/aspose.psd/pen/) puede terminar una línea. |
| [LineJoin](/psd/python-net/aspose.psd/linejoin/) | Especifica cómo unir segmentos consecutivos de línea o curva en una figura (subruta) contenida en un objeto [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) | Especifica el orden de las operaciones de transformación de matrices. |
| [PdfComplianceVersion](/psd/python-net/aspose.psd/pdfcomplianceversion/) | Especifica el nivel de cumplimiento PDF para el archivo de salida. |
| [PenAlignment](/psd/python-net/aspose.psd/penalignment/) | Especifica la alineación de un objeto [Pen](/psd/python-net/aspose.psd/pen/) en relación con la línea teórica de ancho cero. |
| [PenType](/psd/python-net/aspose.psd/pentype/) | Especifica el tipo de relleno que un objeto [Pen](/psd/python-net/aspose.psd/pen/) usa para rellenar líneas. |
| [PixelFormat](/psd/python-net/aspose.psd/pixelformat/) | El significado real del formato de datos de píxel. |
| [ResizeType](/psd/python-net/aspose.psd/resizetype/) | Especifica el tipo de redimensionamiento. |
| [ResolutionUnit](/psd/python-net/aspose.psd/resolutionunit/) | Enumeración de unidad de resolución. |
| [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype/) | Especifica cuánto se rota una imagen y el eje utilizado para voltear la imagen. |
| [SeekOrigin](/psd/python-net/aspose.psd/seekorigin/) | Proporciona los campos que representan puntos de referencia en [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) para la búsqueda. |
| [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode/) | Especifica si se aplica suavizado (antialiasing) a líneas y curvas y a los bordes de áreas rellenas. |
| [StringAlignment](/psd/python-net/aspose.psd/stringalignment/) | Especifica la alineación de una cadena de texto respecto a su rectángulo de diseño. |
| [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute/) | La enumeración especifica cómo sustituir dígitos en una cadena según la configuración regional o el idioma del usuario. |
| [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) | Especifica la información de visualización y diseño para cadenas de texto. |
| [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) | Especifica cómo recortar caracteres de una cadena que no cabe completamente en una forma de diseño. |
| [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint/) | Especifica la calidad del renderizado de texto. |
| [WarpMode](/psd/python-net/aspose.psd/warpmode/) | Especifica el tipo de transformación de deformación aplicada. |
| [WrapMode](/psd/python-net/aspose.psd/wrapmode/) | Especifica cómo se mosaica una textura o degradado cuando es más pequeña que el área a rellenar. |
