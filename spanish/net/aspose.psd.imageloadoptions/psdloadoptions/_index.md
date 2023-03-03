---
title: Class PsdLoadOptions
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.ImageLoadOptions.PsdLoadOptions clase. Opciones de carga de psd
type: docs
weight: 4770
url: /es/net/aspose.psd.imageloadoptions/psdloadoptions/
---
## PsdLoadOptions class

Opciones de carga de psd

```csharp
public class PsdLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Obtiene o establece si guardar con la imagen renderizada, con o sin una transformación warp. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Obtiene o establece el[`Image`](../../aspose.psd/image/) fondo[`Color`](../../aspose.psd/color/) . |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Obtiene o establece el modo de recuperación de datos. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Obtiene o establece un valor que indica si [ignorar canal alfa]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Obtiene o establece un valor que indica si se ignorará el ancho fijo de la capa de texto PSD en la ejecución de la operación UpdateText. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Obtiene o establece un valor que indica si [la carga afecta el recurso] (por defecto, el recurso no está cargado). Cuando se establece esta opción, solo los efectos admitidos se renderizarán en la imagen fusionada final. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Obtiene o establece el controlador de eventos de progreso. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Obtiene o establece un valor que indica si [usar modo de solo lectura]. Este es el modo de solo lectura, compatible con compatibilidad idéntica con Adobe Photoshop. Cuando se establece esta opción, todos los cambios aplicados a las capas no se guardarán en la imagen final. Todos los datos se utilizan de la sección ImageData, por lo que es idéntico a Photoshop. Por defecto, todas las imágenes cargadas no son idénticas a las compatibles con Adobe Photoshop. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Obtiene o establece un valor que indica si [usar disco para cargar el recurso de efectos] (de forma predeterminada, se usa el disco para cargar el recurso de efectos, pero se puede usar la memoria si es suficiente configurando este valor en falso). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Obtiene o establece un valor que indica si se debe aplicar la conversión de perfil ICC. |

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

* class [LoadOptions](../../aspose.psd/loadoptions/)
* espacio de nombres [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* asamblea [Aspose.PSD](../../)


