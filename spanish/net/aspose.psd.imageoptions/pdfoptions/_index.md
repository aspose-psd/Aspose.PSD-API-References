---
title: Class PdfOptions
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.ImageOptions.PdfOptions clase. Las opciones de PDF.
type: docs
weight: 4870
url: /es/net/aspose.psd.imageoptions/pdfoptions/
---
## PdfOptions class

Las opciones de PDF.

```csharp
public class PdfOptions : ImageOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfOptions](pdfoptions/)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se usará para dibujar texto al exportar a ráster, si la fuente de capa existente en el archivo PSD no se presenta en el sistema). Para tomar el nombre correcto de la fuente predeterminada, se puede usar el siguiente fragmento de código : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familias = col.Familias; string defaultFontName = familias[0].Nombre; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Obtiene o establece un valor que indica si [fotograma completo]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Las opciones multipágina |
| [PageSize](../../aspose.psd.imageoptions/pdfoptions/pagesize/) { get; set; } | Obtiene o establece el tamaño de la página. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Obtiene o establece la paleta de colores. |
| [PdfCoreOptions](../../aspose.psd.imageoptions/pdfoptions/pdfcoreoptions/) { get; set; } | Las opciones principales de PDF |
| [PdfDocumentInfo](../../aspose.psd.imageoptions/pdfoptions/pdfdocumentinfo/) { get; set; } | Obtiene o establece metadatos para document. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Obtiene o establece el controlador de eventos de progreso. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Obtiene o establece la configuración de resolución. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Obtiene o establece la fuente para crear la imagen en. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Obtiene o establece las opciones de rasterización de vectores. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clona esta instancia. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina la instancia actual. |

### Ejemplos

El siguiente ejemplo demuestra cómo puede exportar archivos de Adobe Illustrator a formato PDF en Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

El siguiente ejemplo demuestra que AsposePSD admite la exportación de archivos PSB a un formato PSD.

```csharp
[C#]

// Admite guardar PSB como PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

El siguiente código guarda PsdImage como documento PDF con texto seleccionable.

```csharp
[C#]

// Guardar PSD en PDF no proporciona texto seleccionable
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

El siguiente ejemplo demuestra la compatibilidad con la exportación de PsdImage a formato Pdf.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"1.psd",
    @"little.psb",
    @"psb3.psb",
    @"inRgb16.psd",
    @"ALotOfElementTypes.psd",
    @"ColorOverlayAndShadowAndMask.psd",
    @"ThreeRegularLayersSemiTransparent.psd"
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string sourceFileName = sourcesFiles[i];
    using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
    {
        string outFileName = "PsdToPdf" + i + ".pdf";
        image.Save(outFileName, new PdfOptions());
    }
}
```

### Ver también

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* espacio de nombres [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* asamblea [Aspose.PSD](../../)


