---
title: "Sınıf VectorPathDataResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPathDataResource sınıf. VectorPathDataResource sınıf. Bu kaynak vektör katman maskesi hakkında bilgi içerir."
type: docs
weight: 3740
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/
---
{{< psd/tize >}}
## VectorPathDataResource class

VectorPathDataResource sınıfı. Bu kaynak vektör katman maskesi hakkında bilgi içerir.

```csharp
public abstract class VectorPathDataResource : LayerResource, IVectorPathData
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | Bu örneğin devre dışı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | Bu örneğin ters çevrilmiş olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | Bu örneğin bağlanmamış olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | Yol kayıtlarını alır veya ayarlar. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | Sürümü alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Örnekler

Aşağıdaki örnek Katman Vektör Maskeleri işleme desteğini gösterir. Yolların düzenlenmesinin nasıl çalıştığını ve Aspose.PSD'nin son görüntüyü nasıl çizdiğini açıklar.

```csharp
[C#]

string sourceFileName = "DifferentLayerMasks_Source.psd";
string exportPath = "DifferentLayerMasks_Export.psd";
string exportPathPng = "DifferentLayerMasks_Export.png";

// Okuma
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    // Vektör yol noktalarında değişiklik yapın
    foreach (var layer in image.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            var resource = layerResource as VectorPathDataResource;
            if (resource != null)
            {
                foreach (var pathRecord in resource.Paths)
                {
                    var bezierKnotRecord = pathRecord as BezierKnotRecord;
                    if (bezierKnotRecord != null)
                    {
                        Point p0 = bezierKnotRecord.Points[0];
                        bezierKnotRecord.Points[0] = bezierKnotRecord.Points[2];
                        bezierKnotRecord.Points[2] = p0;
                        break;
                    }
                }
            }
        }
    }

    // Dışa Aktarma
    image.Save(exportPath);
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ayrıca Bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


