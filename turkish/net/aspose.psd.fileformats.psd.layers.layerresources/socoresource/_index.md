---
title: "Sınıf SoCoResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoCoResource sınıfı. Sınıf SoCoResource. Bu kaynak Renk Doldurma Katmanları hakkında bilgi içerir"
type: docs
weight: 3360
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---
{{< psd/tize >}}
## SoCoResource class

SoCoResource sınıfı. Bu kaynak Renk Doldurma Katmanları hakkında bilgi içerir.

```csharp
public class SoCoResource : FillLayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SoCoResource](socoresource/)() | `SoCoResource` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/) { get; set; } | RGB rengini alır. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

## Örnekler

Aşağıdaki örnek, SoCoResource'ı (Renk Doldurma Katmanı için Katman Kaynağı) nasıl düzenleyeceğinizi gösterir

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // FillLayer bulunması
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Katman Kaynak Listesinde SoCoResource bulunması
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // SoCoResource Renk özelliğini ayarlama
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### Ayrıca Bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


