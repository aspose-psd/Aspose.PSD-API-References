---
title: "Delegado ProgressEventHandler"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Referencia a la función manejadora del evento de progreso"
type: docs
weight: 5780
url: /es/net/aspose.psd/progresseventhandler/
---
{{< psd/tize >}}
## ProgressEventHandler delegate

Referencia a la función manejadora del evento de progreso

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| información | ProgressEventHandlerInfo | Los datos del controlador de eventos de progreso. |

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

* class [ProgressEventHandlerInfo](../../aspose.psd.progressmanagement/progresseventhandlerinfo/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


