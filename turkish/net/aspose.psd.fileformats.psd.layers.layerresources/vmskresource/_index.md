---
title: Class VmskResource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VmskResource sınıf. Class VmskResource. Bu kaynak mask vektör katmanı hakkında bilgi içerir.
type: docs
weight: 3360
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/
---
## VmskResource class

Class VmskResource. Bu kaynak, mask vektör katmanı hakkında bilgi içerir.

```csharp
public class VmskResource : VectorPathDataResource
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [VmskResource](vmskresource/#constructor)() | Yeni bir örneğini başlatır.`VmskResource` sınıf. |
| [VmskResource](vmskresource/#constructor_1)(byte[]) | Yeni bir örneğini başlatır.`VmskResource` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | Bu örneğin devre dışı bırakılıp bırakılmadığını gösteren bir değer alır veya ayarlar. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | Bu örneğin ters çevrildiğini gösteren bir değer alır veya ayarlar. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | Bu örneğin bağlantılı olup olmadığını gösteren bir değer alır veya ayarlar. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vmskresource/key/) { get; } | Katman kaynak anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | Katman kaynak uzunluğunu bayt cinsinden alır. |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | Yol kayıtlarını alır veya ayarlar. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/psdversion/) { get; } | psd sürümünü alır. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/signature/) { get; } | İmzayı alır. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | Sürümü alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış kapsayıcısına kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | a döndürürString bu örneği temsil eder. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vmskresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

### Örnekler

Aşağıdaki örnek, VmskResource kaynak yükleme desteğini göstermektedir. Yolların düzenlenmesi nasıl çalışır?

```csharp
[C#]

[Test]
public void TestPsdNet106()
{
    string sourceFileName = "Rectangle.psd";
    string exportPath = "Rectangle_changed.psd";
    var im = (PsdImage)Image.Load(sourceFileName);
    using (im)
    {
        var resource = GetVmskResource(im);
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
            throw new Exception("VmskResource was read wrong");
        }
        var pathFillRule = (PathFillRuleRecord)resource.Paths[0];
        var initialFillRule = (InitialFillRuleRecord)resource.Paths[1];
        var subpathLength = (LengthRecord)resource.Paths[2];
        // Yol doldurma kuralı herhangi bir ek bilgi içermez
        if (pathFillRule.Type != VectorPathType.PathFillRuleRecord ||
         initialFillRule.Type != VectorPathType.InitialFillRuleRecord ||
         initialFillRule.IsFillStartsWithAllPixels != false ||
         subpathLength.Type != VectorPathType.ClosedSubpathLengthRecord ||
         subpathLength.IsClosed != true ||
         subpathLength.IsOpen != false)
        {
            throw new Exception("VmskResource paths were read wrong");
        }
        // düzenleme
        resource.IsDisabled = true;
        resource.IsInverted = true;
        resource.IsNotLinked = true;
        var bezierKnot = (BezierKnotRecord)resource.Paths[3];
        bezierKnot.Points[0] = new Point(0, 0);
        bezierKnot = (BezierKnotRecord)resource.Paths[4];
        bezierKnot.Points[0] = new Point(8039797, 10905190);
        initialFillRule.IsFillStartsWithAllPixels = true;
        subpathLength.IsClosed = false;
        im.Save(exportPath);
    }
}

private VmskResource GetVmskResource(PsdImage image)
{
    var layer = image.Layers[1];
    VmskResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VmskResource)
        {
            resource = (VmskResource)resources[i];
            break;
        }
    }
    if (resource == null)
    {
        throw new Exception("VmskResource not found");
    }
    return resource;
}
```

### Ayrıca bakınız

* class [VectorPathDataResource](../vectorpathdataresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* toplantı [Aspose.PSD](../../)


