---
title: PtFlResource.AlignWithLayer
second_title: Referencia de API de Aspose.PSD para .NET
description: PtFlResource propiedad. Obtiene o establece un valor que indica si alinear con la capa.
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/alignwithlayer/
---
## PtFlResource.AlignWithLayer property

Obtiene o establece un valor que indica si [alinear con la capa].

```csharp
public bool AlignWithLayer { get; set; }
```

### El valor de la propiedad

`verdadero` si [alinear con la capa]; de lo contrario,`FALSO` .

### Ejemplos

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
                    // No tenemos datos de patrones en PattResource, por lo que podemos agregarlos.
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

* class [PtFlResource](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../ptflresource/)
* asamblea [Aspose.PSD](../../../)


