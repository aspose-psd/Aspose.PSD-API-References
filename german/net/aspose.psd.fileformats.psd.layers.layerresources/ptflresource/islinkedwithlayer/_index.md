---
title: "PtFlResource.IsLinkedWithLayer"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PtFlResource-Eigenschaft. Gibt einen Wert zurück oder legt ihn fest, der angibt, ob diese Instanz mit der Ebene verknüpft ist"
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer/
---
{{< psd/tize >}}
## PtFlResource.IsLinkedWithLayer property

Liefert oder setzt einen Wert, der angibt, ob diese Instanz mit dem Layer verknüpft ist.

```csharp
public bool IsLinkedWithLayer { get; set; }
```

### Property Value

`true`, wenn diese Instanz mit der Ebene verknüpft ist; andernfalls `false`.

## Beispiele

Das folgende Beispiel demonstriert die Unterstützung des Ladens und Bearbeitens einer PtFlResource‑Ressource.

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
                    // Lesen
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

                    // Bearbeiten
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // Wir haben keine Musterdaten in PattResource, also können wir sie hinzufügen.
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

### Siehe auch

* class [PtFlResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


