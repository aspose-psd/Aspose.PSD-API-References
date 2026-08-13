---
title: "Sınıf VsmsResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VsmsResource sınıfı. VsmsResource sınıfı. Bu kaynak, vektör katman maskesi hakkında bilgi içerir."
type: docs
weight: 3780
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/
---
{{< psd/tize >}}
## VsmsResource class

VsmsResource sınıfı. Bu kaynak vektör katman maskesi hakkında bilgi içerir.

```csharp
public class VsmsResource : VectorPathDataResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [VsmsResource](vsmsresource/#constructor)() | Yeni bir `VsmsResource` sınıfı örneği başlatır. |
| [VsmsResource](vsmsresource/#constructor_1)(byte[]) | Yeni bir `VsmsResource` sınıfı örneği başlatır. |

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

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

## Örnekler

Aşağıdaki örnek, VsmsResource kaynağının yüklenmesini desteklediğini gösterir. Yolların düzenlenmesinin nasıl çalıştığını gösterir.

```csharp
[C#]

[Test]
public void TestPsdNet140()
{
    // VsmsResource Desteği
    string sourceFileName = "EmptyRectangle.psd";
    string exportPath = "EmptyRectangle_changed.psd";
    var im = (PsdImage)Image.Load(sourceFileName);
    using (im)
    {
        var resource = GetVsmsResource(im);
        // Okuma
        if (resource.IsDisabled != false ||
            resource.IsInverted != false ||
            resource.IsNotLinked != false ||
            resource.Paths.Length != 7 ||
            resource.Paths[0].Type != VectorPathType.PathFillRuleRecord ||
            resource.Paths[1].Type != VectorPathType.InitialFillRuleRecord ||
            resource.Paths[2].Type != VectorPathType.ClosedSubpathLengthRecord ||
            resource.Paths[3].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[4].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[5].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[6].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked)
        {
            throw new Exception("VsmsResource was read wrong");
        }

        var pathFillRule = (PathFillRuleRecord)resource.Paths[0];
        var initialFillRule = (InitialFillRuleRecord)resource.Paths[1];
        var subpathLength = (LengthRecord)resource.Paths[2];

        // Yol doldurma kuralı ek bilgi içermez
        if (pathFillRule.Type != VectorPathType.PathFillRuleRecord ||
        initialFillRule.Type != VectorPathType.InitialFillRuleRecord ||
        initialFillRule.IsFillStartsWithAllPixels != false ||
        subpathLength.Type != VectorPathType.ClosedSubpathLengthRecord ||
        subpathLength.IsClosed != true ||
        subpathLength.IsOpen != false)
        {
            throw new Exception("VsmsResource paths were read wrong");
        }

        // Düzenleme
        resource.IsDisabled = true;
        resource.IsInverted = true;
        resource.IsNotLinked = true;
        var bezierKnot = (BezierKnotRecord)resource.Paths[3];
        bezierKnot.Points[0] = new Point(0, 0);
        bezierKnot = (BezierKnotRecord)resource.Paths[4];
        bezierKnot.Points[0] = new Point(8039798, 10905191);
        initialFillRule.IsFillStartsWithAllPixels = true;
        subpathLength.IsClosed = false;
        im.Save(exportPath);
    }
}

private VsmsResource GetVsmsResource(PsdImage image)
{
    var layer = image.Layers[1];
    VsmsResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VsmsResource)
        {
            resource = (VsmsResource)resources[i];
            break;
        }
    }
    if (resource == null)
    {
        throw new Exception("VsmsResource not found");
    }
    return resource;
}
```

### Ayrıca Bakınız

* class [VectorPathDataResource](../vectorpathdataresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


