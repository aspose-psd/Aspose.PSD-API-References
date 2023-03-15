---
title: PtFlResource.IsLinkedWithLayer
second_title: Aspose.PSD for .NET API Referansı
description: PtFlResource mülk. Bu örneğin layer. ile bağlantılı olup olmadığını gösteren bir değer alır veya ayarlar.
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer/
---
## PtFlResource.IsLinkedWithLayer property

Bu örneğin layer. ile bağlantılı olup olmadığını gösteren bir değer alır veya ayarlar.

```csharp
public bool IsLinkedWithLayer { get; set; }
```

### Mülk değeri

`doğru` bu örnek katmanla bağlantılıysa; aksi takdirde,`YANLIŞ` .

### Örnekler

Aşağıdaki örnek, bir PtFlResource kaynağını yükleme ve düzenleme desteğini gösterir.

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
                    // Okuma
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

                    // düzenleme
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // Verileri PattResource'ta modellemedik, bu yüzden onu ekleyebiliriz.
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

### Ayrıca bakınız

* class [PtFlResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../ptflresource/)
* toplantı [Aspose.PSD](../../../)


