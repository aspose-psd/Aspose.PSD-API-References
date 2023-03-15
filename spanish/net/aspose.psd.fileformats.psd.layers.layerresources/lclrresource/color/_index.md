---
title: LclrResource.Color
second_title: Referencia de API de Aspose.PSD para .NET
description: LclrResource propiedad. Obtiene o establece el color de la capa.
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/
---
## LclrResource.Color property

Obtiene o establece el color de la capa.

```csharp
public SheetColorHighlightEnum Color { get; set; }
```

### El valor de la propiedad

El color.

### Ejemplos

El siguiente ejemplo demuestra cómo puede cambiar el resaltado de color de hoja en Aspose.PSD (configuración de color de hoja)

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// En el archivo, los colores de las capas resaltadas están en este orden
SheetColorHighlightEnum[] sheetColorsArr = new SheetColorHighlightEnum[] {
    SheetColorHighlightEnum.Red,
    SheetColorHighlightEnum.Orange,
    SheetColorHighlightEnum.Yellow,
    SheetColorHighlightEnum.Green,
    SheetColorHighlightEnum.Blue,
    SheetColorHighlightEnum.Violet,
    SheetColorHighlightEnum.Gray,
    SheetColorHighlightEnum.NoColor
};

// El color de hoja de capa se usa para resaltar capas visualmente. 
// Por ejemplo, puede actualizar algunas capas en PSD y luego resaltar con color la capa que desea llamar la atención.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Los colores deben invertirse
    Array.Reverse(sheetColorsArr);
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
}

void CheckSheetColorsAndRerverse(SheetColorHighlightEnum[] sheetColors, PsdImage img)
{
    int layersCount = img.Layers.Length;
    for (int layerIndex = 0; layerIndex < layersCount; layerIndex++)
    {
        Layer layer = img.Layers[layerIndex];
        LayerResource[] resources = layer.Resources;
        foreach (LayerResource layerResource in resources)
        {
            // El recurso lcrl siempre se presenta en la lista de recursos del archivo psd.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Inverso de los colores de la hoja de estilo. Configuración del resaltado de color de capa.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Ver también

* enum [SheetColorHighlightEnum](../../sheetcolorhighlightenum/)
* class [LclrResource](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../lclrresource/)
* asamblea [Aspose.PSD](../../../)


