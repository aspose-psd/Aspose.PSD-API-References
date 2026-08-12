---
title: "Clase ImageOptionsBase"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.ImageOptionsBase. Las opciones base de la imagen"
type: docs
weight: 5480
url: /es/net/aspose.psd/imageoptionsbase/
---
{{< psd/tize >}}
## ImageOptionsBase class

Las opciones base de la imagen.

```csharp
public abstract class ImageOptionsBase : DisposableObject
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Obtiene o establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de la capa existente en el archivo PSD no está presente en el sistema). Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Obtiene o establece un valor que indica si [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Las opciones multipágina |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Obtiene o establece la paleta de colores. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Obtiene o establece el controlador del evento de progreso. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Obtiene o establece la configuración de resolución. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Obtiene o establece la fuente donde crear la imagen. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Obtiene o establece las opciones de rasterización vectorial. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clona esta instancia. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |

### Ver también

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


