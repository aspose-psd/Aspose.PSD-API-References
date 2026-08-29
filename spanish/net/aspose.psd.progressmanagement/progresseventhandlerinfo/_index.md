---
title: "Clase ProgressEventHandlerInfo"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo class. Esta clase representa información sobre el progreso de operaciones de carga/guardado/exportación de imágenes que puede ser utilizada en una aplicación externa para mostrar el progreso de la conversión al usuario final"
type: docs
weight: 5800
url: /es/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
{{< psd/tize >}}
## ProgressEventHandlerInfo class

Esta clase representa información sobre el progreso de las operaciones de carga/guardado/exportación de imágenes, que puede ser utilizada en una aplicación externa para mostrar el progreso de la conversión al usuario final

```csharp
public class ProgressEventHandlerInfo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | Obtiene la descripción del evento |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Obtiene el tipo del evento. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Obtiene el límite superior del valor de progreso. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | Obtiene el valor actual de progreso. |

## Ejemplos

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

### Ver también

* namespace [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* assembly [Aspose.PSD](../../)


