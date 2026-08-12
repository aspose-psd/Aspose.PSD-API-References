---
title: "FillLayer.ReplaceNonTransparentColors"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método FillLayer. Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para mantener bordes suaves. Nota: si lo usas en imágenes sin transparencia, todos los colores se reemplazarán por uno único."
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
{{< psd/tize >}}
## FillLayer.ReplaceNonTransparentColors method

Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para mantener bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán por uno solo.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorArgb | Int32 | Nuevo valor ARGB de color para reemplazar colores no transparentes. |

## Ejemplos

El siguiente código demuestra el soporte del modo de color CMYK de 16 bits y la capacidad de dibujar usando la clase Aspose.PSD.Graphics.

```csharp
[C#]

string srcFile = "cub16bit_cmyk.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Ver también

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


