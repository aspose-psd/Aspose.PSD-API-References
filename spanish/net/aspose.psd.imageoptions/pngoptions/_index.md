---
title: "Clase PngOptions"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.ImageOptions.PngOptions. Opciones de creación del formato de archivo png"
type: docs
weight: 5370
url: /es/net/aspose.psd.imageoptions/pngoptions/
---
{{< psd/tize >}}
## PngOptions class

Las opciones de creación del formato de archivo png.

```csharp
public class PngOptions : ImageOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PngOptions](pngoptions/#constructor)() | Inicializa una nueva instancia de la clase `PngOptions`. |
| [PngOptions](pngoptions/#constructor_1)(PngOptions) | Inicializa una nueva instancia de la clase `PngOptions`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BitDepth](../../aspose.psd.imageoptions/pngoptions/bitdepth/) { get; set; } | La profundidad de bits. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Obtiene o establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [ColorType](../../aspose.psd.imageoptions/pngoptions/colortype/) { get; set; } | Obtiene o establece el tipo de color. |
| [CompressionLevel](../../aspose.psd.imageoptions/pngoptions/compressionlevel/) { get; set; } | El nivel de compresión de la imagen png en el rango 0-9, donde 9 es compresión máxima y 0 es modo de almacenamiento. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de la capa existente en el archivo PSD no está presente en el sistema). Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| [FilterType](../../aspose.psd.imageoptions/pngoptions/filtertype/) { get; set; } | Obtiene o establece el tipo de filtro utilizado durante el proceso de guardado del archivo png. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Obtiene o establece un valor que indica si [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Las opciones multipágina |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Obtiene o establece la paleta de colores. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Obtiene o establece el controlador del evento de progreso. |
| [Progressive](../../aspose.psd.imageoptions/pngoptions/progressive/) { get; set; } | Obtiene o establece un valor que indica si este `PngOptions` es progresivo. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Obtiene o establece la configuración de resolución. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Obtiene o establece la fuente donde crear la imagen. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Obtiene o establece las opciones de rasterización vectorial. |
| override [XmpData](../../aspose.psd.imageoptions/pngoptions/xmpdata/) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clona esta instancia. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [DefaultCompressionLevel](../../aspose.psd.imageoptions/pngoptions/defaultcompressionlevel/) | El nivel de compresión predeterminado. |

## Ejemplos

El siguiente ejemplo muestra cómo puede exportar un archivo AI a formato PSD y PNG en Aspose.PSD

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Este ejemplo muestra el uso de diferentes clases del espacio de nombres SaveOptions para propósitos de exportación. Una imagen de tipo Psd se carga en una instancia de Image y luego se exporta a varios formatos.

```csharp
[C#]

//Cargar una imagen existente en una instancia de la clase Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Exportar al formato de archivo BMP usando las opciones predeterminadas
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Exportar al formato de archivo JPEG usando las opciones predeterminadas
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Exportar al formato de archivo JPEG 2000 usando las opciones predeterminadas
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Exportar al formato de archivo PNG usando las opciones predeterminadas
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Exportar al formato de archivo TIFF usando las opciones predeterminadas
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

El siguiente ejemplo muestra cómo puede usar el modo de fusión de capa PassThrough en Aspose.PSD

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

El siguiente ejemplo demuestra que el progreso de conversión del documento funciona correctamente y sin excepciones.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

Este ejemplo usa la clase Graphics para crear formas primitivas en la superficie de la Imagen. Para demostrar la operación, el ejemplo crea una nueva Imagen en formato PSD y dibuja formas primitivas en la superficie de la Imagen usando los métodos Draw expuestos por la clase Graphics, luego la exporta al formato de archivo PSD.

```csharp
[C#]

//Crea una instancia de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inicializa una instancia de la clase Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Limpia la superficie Graphics
    graphics.Clear(Color.Wheat);

    //Dibuje un arco especificando el objeto Pen con color negro, 
    //un Rectángulo que rodea el arco, ángulo de inicio y ángulo de barrido
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Dibuje una curva Bézier especificando el objeto Pen con color azul y los puntos coordenados.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Dibuje una curva especificando el objeto Pen con color verde y una matriz de puntos
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Dibuje una elipse usando el objeto Pen y un rectángulo circundante
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Dibuje una línea 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Dibuje un segmento de pastel
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Dibuje un polígono especificando el objeto Pen con color rojo y una matriz de puntos
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Dibuje un rectángulo
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Cree un objeto SolidBrush y establezca sus diversas propiedades
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Dibuje una cadena usando el objeto SolidBrush y la Fuente, en un punto específico
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Cree una instancia de PngOptions y establezca sus diversas propiedades
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // Guarda todos los cambios.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Ver también

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


