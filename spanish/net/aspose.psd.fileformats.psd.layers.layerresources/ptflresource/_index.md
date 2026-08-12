---
title: "Clase PtFlResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PtFlResource. Clase PtFlResource. Contiene datos de capa de relleno de patrón"
type: docs
weight: 3310
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---
{{< psd/tize >}}
## PtFlResource class

Clase PtFlResource. Contiene datos de capa Pattern Fill.

```csharp
public class PtFlResource : FillLayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PtFlResource](ptflresource/#constructor)() | Inicializa una nueva instancia de la clase `PtFlResource`. |
| [PtFlResource](ptflresource/#constructor_1)(string, string) | Inicializa una nueva instancia de la clase `PtFlResource`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/alignwithlayer/) { get; set; } | Obtiene o establece un valor que indica si [align with layer]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/angle/) { get; set; } | Obtiene o establece el ángulo. |
| [IsLinkedWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer/) { get; set; } | Obtiene o establece un valor que indica si esta instancia está vinculada con la capa. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave del recurso de capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/length/) { get; } | Obtiene la longitud del recurso de capa en bytes. |
| [Offset](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/offset/) { get; set; } | Obtiene o establece el desplazamiento. |
| [PatternId](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternid/) { get; set; } | Obtiene o establece el identificador del patrón. |
| [PatternName](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternname/) { get; set; } | Obtiene o establece el nombre del patrón. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/scale/) { get; set; } | Obtiene o establece la escala. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtiene la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/save/)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve una String que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

## Ejemplos

El siguiente ejemplo demuestra el soporte de la carga y edición de un recurso PtFlResource.

```csharp
[C#]

string sourceFileName = "PatternFillLayer.psd";
string exportPath = "PtFlResource_Edited.psd";
double tolerance = 0.0001;
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var resources = fillLayer.Resources;
            foreach (var res in resources)
            {
                if (res is PtFlResource)
                {
                    // Lectura
                    PtFlResource resource = (PtFlResource)res;
                    if (
                        resource.Offset.X != -46 ||
                        resource.Offset.Y != -45 ||
                        resource.PatternId != "a6818df2-7532-494e-9615-8fdd6b7f38e5\0" ||
                        resource.PatternName != "$$$/Presets/Patterns/OpticalSquares=Optical Squares\0" ||
                        resource.AlignWithLayer != true ||
                        resource.IsLinkedWithLayer != true ||
                        !(Math.Abs(resource.Scale - 50) < tolerance))
                    {
                        throw new Exception("PtFl Resource was read incorrect");
                    }

                    // Edición
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // No tenemos datos de patrón en PattResource, así que podemos añadirlos.
                    var fillSettings = (PatternFillSettings)fillLayer.FillSettings;
                    fillSettings.PatternData = new int[]
                    {
                        Color.Black.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                    };
                    fillSettings.PatternHeight = 1;
                    fillSettings.PatternWidth = 4;
                    fillSettings.PatternName = "$$$/Presets/Patterns/VerticalLine=Vertical Line New\0";
                    fillSettings.PatternId = Guid.NewGuid().ToString() + "\0";
                    fillLayer.Update();
                }
                break;
            }
            break;
        }
    }

    im.Save(exportPath);
}
```

### Ver también

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


