---
title: "Clase PsdLoadOptions"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.ImageLoadOptions.PsdLoadOptions. Opciones de carga Psd"
type: docs
weight: 5250
url: /es/net/aspose.psd.imageloadoptions/psdloadoptions/
---
{{< psd/tize >}}
## PsdLoadOptions class

Opciones de carga Psd

```csharp
public class PsdLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AllowNonChangedLayerRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/) { get; set; } | Obtiene o establece si se deben conservar los píxeles originales de la capa durante el renderizado cuando la capa no ha sido modificada. |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Obtiene o establece si se debe guardar con la imagen renderizada, con o sin una transformación de deformación. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Obtiene o establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Obtiene o establece el fondo de la [`Image`](../../aspose.psd/image/) y el [`Color`](../../aspose.psd/color/). |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Obtiene o establece el modo de recuperación de datos. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Obtiene o establece un valor que indica si se debe [ignore alpha channel]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Obtiene o establece un valor que indica si se debe ignorar el ancho fijo de la capa de texto PSD al ejecutar la operación UpdateText. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Obtiene o establece un valor que indica si se debe [load effects resource] (por defecto el recurso no se carga). Cuando se establece, solo los efectos compatibles se renderizarán en la imagen final combinada. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Obtiene o establece el controlador del evento de progreso. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Obtiene o establece un valor que indica si se debe [use read only mode]. Este es un modo de solo lectura, compatible para lograr una compatibilidad idéntica con Adobe Photoshop. Cuando esta opción está activada, todos los cambios aplicados a las capas no se guardarán en la imagen final. Todos los datos se usan de la sección ImageData, por lo que es idéntico a Photoshop. Por defecto, todas las imágenes cargadas no son idénticas a la compatibilidad de Adobe Photoshop. |
| [ReadOnlyType](../../aspose.psd.imageloadoptions/psdloadoptions/readonlytype/) { get; set; } | Obtiene o establece el modo de solo lectura usado al cargar una imagen PSD. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Obtiene o establece un valor que indica si se debe [use disk for load effects resource] (por defecto se usa el disco para cargar recursos de efectos, pero se puede usar memoria si es suficiente al establecer este valor en false). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Obtiene o establece un valor que indica si se debe aplicar la conversión del perfil ICC. |

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

* class [LoadOptions](../../aspose.psd/loadoptions/)
* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


