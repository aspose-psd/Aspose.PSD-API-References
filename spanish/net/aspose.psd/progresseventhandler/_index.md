---
title: Delegate ProgressEventHandler
second_title: Referencia de API de Aspose.PSD para .NET
description: Referencia de la función del controlador de eventos de progreso
type: docs
weight: 5280
url: /es/net/aspose.psd/progresseventhandler/
---
## ProgressEventHandler delegate

Referencia de la función del controlador de eventos de progreso

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| info | ProgressEventHandlerInfo | Los datos del controlador de eventos de progreso. |

### Ejemplos

El siguiente ejemplo demuestra que el progreso de conversión de documentos funciona correctamente y sin excepción.

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
* espacio de nombres [Aspose.PSD](../../aspose.psd/)
* asamblea [Aspose.PSD](../../)


