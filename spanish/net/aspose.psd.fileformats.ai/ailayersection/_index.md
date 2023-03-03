---
title: Class AiLayerSection
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Ai.AiLayerSection clase. La sección de capa de formato Ai
type: docs
weight: 1270
url: /es/net/aspose.psd.fileformats.ai/ailayersection/
---
## AiLayerSection class

La sección de capa de formato Ai

```csharp
public sealed class AiLayerSection : AiDataSection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | Obtiene o establece el componente de color azul. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | Obtiene o establece el número de color. -1 es el valor de color personalizado de las propiedades Rojo, Verde, Azul. Especifica la configuración de color de la capa. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | Obtiene o establece el valor de atenuación como porcentaje. Reduce la intensidad de las imágenes vinculadas y las imágenes de mapa de bits contenidas en la capa al porcentaje especificado. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | Obtiene o establece el componente de color verde. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | Obtiene o establece un valor que indica si esta capa está atenuada. Reduce la intensidad de las imágenes vinculadas y las imágenes de mapa de bits contenidas en la capa. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | Obtiene o establece un valor que indica si esta capa está bloqueada. Impide cambios en el elemento. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | Obtiene o establece un valor que indica si esta capa es una vista previa. Muestra la ilustración contenida en la capa en color en lugar de como contornos. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | Obtiene o establece un valor que indica si esta capa está impresa. Hace que la ilustración contenida en la capa sea imprimible si es verdadero. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | Obtiene o establece un valor que indica si se muestra esta capa. Muestra todas las ilustraciones contenidas en la capa en la mesa de trabajo si es verdadero. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | Obtiene o establece un valor que indica si esta capa es una capa de plantilla. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | Obtiene o establece el nombre de la capa. Especifica el nombre del elemento tal como aparece en el panel Capas. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | Obtiene las imágenes ráster. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | Obtiene o establece el componente de color rojo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | Agrega la imagen ráster. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina la instancia actual. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | Obtiene los datos de la cadena. |

### Ejemplos

El siguiente código demuestra cómo cargar la configuración de imágenes ráster en archivos con formato AI.

```csharp
[C#]

const double DefaultTolerance = 1e-6;

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

string sourceFile = "sample.ai";
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AiLayerSection layer = image.Layers[0];

    AssertIsTrue(layer.RasterImages != null, "RasterImages property should be not null");
    AssertIsTrue(layer.RasterImages.Length == 1, "RasterImages property should contain exactly one item");

    AiRasterImageSection rasterImage = layer.RasterImages[0];
    AssertIsTrue(rasterImage.Pixels != null, "rasterImage.Pixels property should be not null");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "rasterImage.Pixels property should contain exactly 100 items");
    AssertIsTrue((uint)rasterImage.Pixels[99] == 0xFFB21616, "rasterImage.Pixels[99] should be 0xFFB21616");
    AssertIsTrue((uint)rasterImage.Pixels[19] == 0xFF00FF00, "rasterImage.Pixels[19] should be 0xFF00FF00");
    AssertIsTrue((uint)rasterImage.Pixels[10] == 0xFF01FD00, "rasterImage.Pixels[10] should be 0xFF01FD00");
    AssertIsTrue((uint)rasterImage.Pixels[0] == 0xFF0000FF, "rasterImage.Pixels[0] should be 0xFF0000FF");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Width) < DefaultTolerance, "rasterImage.Width should be 0.99987");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Height) < DefaultTolerance, "rasterImage.Height should be 0.99987");
    AssertIsTrue(Math.Abs(387 - rasterImage.OffsetX) < DefaultTolerance, "rasterImage.OffsetX should be 387");
    AssertIsTrue(Math.Abs(379 - rasterImage.OffsetY) < DefaultTolerance, "rasterImage.OffsetY should be 379");
    AssertIsTrue(Math.Abs(0 - rasterImage.Angle) < DefaultTolerance, "rasterImage.Angle should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.LeftBottomShift) < DefaultTolerance, "rasterImage.LeftBottomShift should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.X) < DefaultTolerance, "rasterImage.ImageRectangle.X should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.Y) < DefaultTolerance, "rasterImage.ImageRectangle.Y should be 0");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Width) < DefaultTolerance, "rasterImage.ImageRectangle.Width should be 10");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Height) < DefaultTolerance, "rasterImage.ImageRectangle.Height should be 10");
}
```

### Ver también

* class [AiDataSection](../aidatasection/)
* espacio de nombres [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* asamblea [Aspose.PSD](../../)


