---
title: "Sınıf PtFlResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PtFlResource sınıfı. Sınıf PtFlResource. Pattern Fill Layer Data içerir."
type: docs
weight: 3310
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---
{{< psd/tize >}}
## PtFlResource class

Sınıf PtFlResource. Desen Doldurma Katmanı Verilerini içerir.

```csharp
public class PtFlResource : FillLayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PtFlResource](ptflresource/#constructor)() | `PtFlResource` sınıfının yeni bir örneğini başlatır. |
| [PtFlResource](ptflresource/#constructor_1)(string, string) | `PtFlResource` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/alignwithlayer/) { get; set; } | [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [Angle](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/angle/) { get; set; } | Açıyı alır veya ayarlar. |
| [IsLinkedWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer/) { get; set; } | Bu örneğin katmanla bağlantılı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [Offset](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/offset/) { get; set; } | Ofseti alır veya ayarlar. |
| [PatternId](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternid/) { get; set; } | Desen tanımlayıcısını alır veya ayarlar. |
| [PatternName](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternname/) { get; set; } | Desenin adını alır veya ayarlar. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/scale/) { get; set; } | Ölçeği alır veya ayarlar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

## Örnekler

Aşağıdaki örnek, bir PtFlResource kaynağının yüklenmesi ve düzenlenmesi desteğini gösterir.

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

                    // Düzenleme
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // PattResource içinde desen verisi yok, bu yüzden ekleyebiliriz.
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

### Ayrıca Bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


