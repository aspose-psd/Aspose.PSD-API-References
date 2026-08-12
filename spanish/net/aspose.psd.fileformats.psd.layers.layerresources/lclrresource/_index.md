---
title: "Clase LclrResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource clase. Clase LclrResource. Este recurso contiene información sobre el color de la capa en la lista de capas de PS. Su único"
type: docs
weight: 2930
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
{{< psd/tize >}}
## LclrResource class

Clase LclrResource. Este recurso contiene información sobre el color de la capa en la lista de capas de PS. Sólo eso

```csharp
public class LclrResource : LayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | Inicializa una nueva instancia de la clase `LclrResource`. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | Inicializa una nueva instancia de la clase `LclrResource`. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | Inicializa una nueva instancia de la clase `LclrResource`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | Obtiene o establece el color de la capa. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave del recurso de capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | Obtiene la longitud del recurso de capa en bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtiene la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve una String que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

## Ejemplos

El siguiente ejemplo demuestra cómo puedes cambiar el resaltado de color de hoja en Aspose.PSD (configuración de color de hoja)

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// En el archivo, los colores de resaltado de las capas están en este orden
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

// El color de hoja de capa se usa para resaltar visualmente las capas.
// Por ejemplo, puedes actualizar algunas capas en PSD y luego resaltar con color la capa a la que deseas atraer la atención.
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
            // El recurso lcrl siempre está presente en la lista de recursos del archivo PSD.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Inversión de los colores de la hoja de estilo. Configuración del resaltado de color de capa.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Ver también

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


