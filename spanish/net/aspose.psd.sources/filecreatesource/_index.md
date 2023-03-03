---
title: Class FileCreateSource
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.Sources.FileCreateSource clase. Representa una fuente de archivo para la creación.
type: docs
weight: 5590
url: /es/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

Representa una fuente de archivo para la creación.

```csharp
public sealed class FileCreateSource : FileSource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Inicializa una nueva instancia del`FileCreateSource` clase. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Inicializa una nueva instancia del`FileCreateSource` clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Obtiene la ruta del archivo a crear. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Obtiene un valor que indica si el archivo será temporal. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Obtiene el contenedor de flujo. |

### Ejemplos

Este ejemplo demuestra el uso de la clase Font y SolidBrush para dibujar cadenas en la superficie de la imagen. El ejemplo crea una nueva imagen y dibuja formas usando Figuras y GraphicsPath

```csharp
[C#]

//Crea una instancia de Imagen
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inicializa una instancia de la clase Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Limpia la superficie gráfica
    graphics.Clear(Color.Wheat);

    //Crea una instancia de Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Crear una instancia de SolidBrush con color rojo
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // Dibujar una cadena
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // crear opciones de exportación.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // guarda todos los cambios
    image.Save("C:\\temp\\output.gif", options);
}
```

### Ver también

* class [FileSource](../filesource/)
* espacio de nombres [Aspose.PSD.Sources](../../aspose.psd.sources/)
* asamblea [Aspose.PSD](../../)


