---
title: "Clase Image"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Image. La imagen es la clase base para todo tipo de imágenes."
type: docs
weight: 5060
url: /es/net/aspose.psd/image/
---
{{< psd/tize >}}
## Image class

La imagen es la clase base para todo tipo de imágenes.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Obtiene o establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [Container](../../aspose.psd/image/container/) { get; } | Obtiene el contenedor `Image`. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Obtiene un valor del formato de archivo |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Obtiene la altura de la imagen. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Obtiene o establece el monitor de interrupciones. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Obtiene un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| [Size](../../aspose.psd/image/size/) { get; } | Obtiene el tamaño de la imagen. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Obtiene un valor que indica si se usa la paleta de la imagen. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Obtiene el ancho de la imagen. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | Crea una nueva imagen usando las opciones de creación especificadas. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | Carga una nueva imagen desde el flujo especificado. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | Carga una nueva imagen desde el archivo especificado. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | Carga una nueva imagen desde el flujo especificado. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | Carga una nueva imagen desde el archivo especificado. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Almacena en caché los datos y asegura que no se carguen datos adicionales desde el [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) subyacente. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Obtiene las opciones predeterminadas. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método [`Save`](../datastreamsupporter/save/), se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método [`Save`](./save/) como segundo parámetro. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | Redimensiona la imagen. Se utiliza el NearestNeighbourResample predeterminado. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | Redimensiona la imagen. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | Redimensiona la imagen. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | Redimensiona la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Redimensiona la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Redimensiona la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | Redimensiona el ancho proporcionalmente. Se utiliza el NearestNeighbourResample predeterminado. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Redimensiona el ancho proporcionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Redimensiona el ancho proporcionalmente. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Rota, voltea o rota y voltea la imagen. |
| [Save](../../aspose.psd/image/save/#save)() | Guarda los datos de la imagen en el flujo subyacente. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Guarda los datos del objeto en el flujo especificado. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Establece la paleta de la imagen. |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | Determina si la imagen puede cargarse desde el flujo especificado. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | Determina si la imagen puede cargarse desde la ruta de archivo especificada. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | Determina si la imagen puede cargarse desde el flujo especificado y, opcionalmente, usando los *loadOptions* especificados. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | Determina si la imagen puede cargarse desde la ruta de archivo especificada y, opcionalmente, usando las opciones de apertura especificadas. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | Obtiene el formato de archivo. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | Obtiene el formato de archivo. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | Obtiene una altura proporcional. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | Obtiene un ancho proporcional. |

## Ejemplos

Este ejemplo crea un nuevo archivo Image en una ubicación de disco especificada por la propiedad Source de la instancia PsdOptions. Se establecen varias propiedades de la instancia PsdOptions antes de crear la imagen real. Especialmente la propiedad Source, que en este caso se refiere a la ubicación real del disco.

```csharp
[C#]

//Cree una instancia de PsdOptions y establezca sus diversas propiedades
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Cree una instancia de FileCreateSource y asígnela como Source para la instancia de PsdOptions
//El segundo parámetro Boolean determina si el archivo a crear es Temporal o no
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Cree una instancia de Image e inicialícela con una instancia de PsdOptions llamando al método Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //realiza algún procesamiento de imagen

    // guarde todos los cambios
    image.Save();
}
```

### Ver también

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


