---
title: Class SoCoResource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoCoResource sınıf. Class SoCoResource. Bu kaynak Renk Dolgu Katmanları hakkında bilgi içerir.
type: docs
weight: 3010
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---
## SoCoResource class

Class SoCoResource. Bu kaynak, Renk Dolgu Katmanları hakkında bilgi içerir.

```csharp
public class SoCoResource : FillLayerResource
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [SoCoResource](socoresource/)() | Yeni bir örneğini başlatır.`SoCoResource` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/) { get; set; } | RGB rengini alır . |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/key/) { get; } | Katman kaynak anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/length/) { get; } | Katman kaynak uzunluğunu bayt cinsinden alır. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0 kısıtlama olmadığını gösterir. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/signature/) { get; } | Katman kaynak imzasını alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış kapsayıcısına kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | a döndürürString bu örneği temsil eder. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

### Örnekler

Aşağıdaki örnek, SoCoResource'u (Renk Dolgu Katmanı için Katman Kaynağı) nasıl düzenlediğinizi göstermektedir.

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // FillLayer'ın Bulunması
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Katman Kaynak Listesinde SoCoResource'un Bulunması
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

                    // SoCoResource Color özelliğinin ayarlanması
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

### Ayrıca bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* toplantı [Aspose.PSD](../../)


