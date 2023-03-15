---
title: Class SmartObjectResource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SmartObjectResource sınıf. Bir PSD dosyasındaki akıllı nesne katmanı hakkında bilgi içeren SmartObjectResource sınıfını tanımlar. Adobe Photoshop görüntülerinde akıllı nesne katmanlarını desteklemek için kullanılan Sold ve Sole kaynakları için temel sınıftır.
type: docs
weight: 2990
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/
---
## SmartObjectResource class

Bir PSD dosyasındaki akıllı nesne katmanı hakkında bilgi içeren SmartObjectResource sınıfını tanımlar. Adobe® Photoshop® görüntülerinde akıllı nesne katmanlarını desteklemek için kullanılan Sold ve Sole kaynakları için temel sınıftır.

```csharp
public abstract class SmartObjectResource : PlacedResource, ISmartObjectLayerResource
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/antialiaspolicy/) { get; set; } | PSD görüntüsündeki akıllı nesne katmanı verilerinin kenar yumuşatma politikasını alır veya ayarlar. |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom/) { get; set; } | PSD görüntüsünde yerleştirilen katmanın alt konumunu alır veya ayarlar. |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds/) { get; set; } | PSD dosyasında yerleştirilen katmanın sınırlarını alır veya ayarlar. |
| [Comp](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/comp/) { get; set; } | PSD dosyasındaki akıllı nesne katmanı verilerinin comp değerini alır veya ayarlar. [Akıllı Nesnelerde katman kompozisyonları](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/compid/) { get; set; } | Alt belge için seçili olan kompozisyonun kimliğini alır veya ayarlar; hiçbiri seçilmezse -1 olur. Kompozisyonlar, tasarımcıların oluşturabileceği bir sayfa düzeninin kompozisyonlarıdır. Katman kompozisyonlarını kullanarak, tek bir Adobe® Photoshop® dosyasında bir mizanpajın birden çok sürümünü oluşturabilir, yönetebilir ve görüntüleyebilirsiniz. Katman kompozisyonu, Katmanlar panelinin bir durumunun anlık görüntüsüdür. Katman kompozisyonları, üç tip katman seçeneğini kaydeder but bu özellik, PSD dosyasındaki akıllı nesne katmanı için Katman Kompozisyonu seçim tanımlayıcısını alır. [Akıllı Nesnelerde katman kompozisyonları](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Crop](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/crop/) { get; set; } | PSD görüntüsündeki akıllı nesne katmanı verilerinin kırpılmasını alır veya ayarlar. |
| [DurationDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationdenominator/) { get; set; } | Süre paydasını alır veya ayarlar. |
| [DurationNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationnumerator/) { get; set; } | Süre payını alır veya ayarlar. |
| [FrameCount](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framecount/) { get; set; } | PSD dosyasındaki akıllı nesne katmanı verilerinin çerçeve sayısını alır veya ayarlar. |
| [FrameStepDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepdenominator/) { get; set; } | Çerçeve adım paydasını alır veya ayarlar. |
| [FrameStepNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepnumerator/) { get; set; } | Çerçeve adımı payını alır veya ayarlar. |
| [Height](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/height/) { get; set; } | Yüksekliği alır veya ayarlar. |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints/) { get; set; } | PSD dosyasındaki yerleştirilmiş katmanın yatay ağ noktalarını alır veya ayarlar. |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit/) { get; set; } | Yatay ağ noktalarının ölçü birimini alır veya ayarlar. |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom/) { get; set; } | Bu örnek çarpıtma stilinin özel olup olmadığını gösteren bir değer alır veya ayarlar. Doğruysa, ağ noktaları içerir. false değerine ayarlanırsa ağ noktalarını siler. |
| override [Items](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/items/) { get; set; } | PSD dosyasındaki akıllı nesne katmanı verilerinin tanımlayıcı öğelerini alır veya ayarlar. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynak anahtarını alır. |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left/) { get; set; } | PSD dosyasında yerleştirilen katmanın sol konumunu alır veya ayarlar. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/length/) { get; } | Akıllı nesne kaynak uzunluğunu bayt cinsinden alır. |
| [NonAffineTransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/nonaffinetransformmatrix/) { get; set; } | PSD dosyasındaki akıllı nesne katmanı verilerinin afin olmayan dönüşüm matrisini alır veya ayarlar. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/originalcompid/) { get; } | Alt belge için geçerli olarak seçili Comp'un orijinal kimliğini alır; hiçbiri seçilmezse -1 olur. Bu özellik, PSD dosyasındaki akıllı nesne katmanı için orijinal katman Comp seçim tanımlayıcısını alır. [Akıllı Nesnelerde katman kompozisyonları](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| override [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/pagenumber/) { get; set; } | PSD dosyasındaki akıllı nesne katmanı verilerinin sayfa numarasını alır veya ayarlar. |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective/) { get; set; } | PSD dosyasına yerleştirilen katmanın perspektif değerini alır veya ayarlar. |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother/) { get; set; } | PSD dosyasına yerleştirilen katmanın perspektif diğer değerini alır veya ayarlar. |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedid/) { get; set; } | PSD görüntüsündeki bu akıllı nesne katmanı verilerinin benzersiz tanımlayıcısını alır veya ayarlar. |
| override [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedlayertype/) { get; set; } | PSD dosyasındaki akıllı nesne katmanı verilerinin türünü alır veya ayarlar. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/psdversion/) { get; } | Akıllı nesne kaynağı için gereken minimum psd sürümünü alır. 0 kısıtlama olmadığını gösterir. |
| [Resolution](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolution/) { get; set; } | PSD dosyasındaki akıllı nesne katmanı verilerinin çözünürlüğünü alır veya ayarlar. |
| [ResolutionUnit](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolutionunit/) { get; set; } | PSD dosyasındaki akıllı nesne katmanı verilerinin çözünürlük ölçüm birimini alır veya ayarlar. |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right/) { get; set; } | PSD dosyasında yerleştirilen katmanın doğru konumunu alır veya ayarlar. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/signature/) { get; } | Akıllı nesne kaynak imzasını alır. |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top/) { get; set; } | PSD görüntüsünde yerleştirilen katmanın en üst konumunu alır veya ayarlar. |
| override [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/totalpages/) { get; set; } | PSD dosyasındaki akıllı nesne katmanı verilerinin toplam sayfa sayısını alır veya ayarlar. |
| override [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/transformmatrix/) { get; set; } | PSD dosyasındaki akıllı nesne katmanı verilerinin dönüşüm matrisini alır veya ayarlar. |
| override [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/uniqueid/) { get; set; } | Akıllı nesne katmanı verilerinin genel benzersiz tanımlayıcısını alır veya ayarlar`SmartObjectResource` PSD görüntüsünde. |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder/) { get; set; } | PSD dosyasındaki yerleştirilen katmanın U sıra değerini alır veya ayarlar. |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value/) { get; set; } | PSD görüntüsündeki yerleştirilmiş katmanın çözgü değerini alır veya ayarlar. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version/) { get; } | PSD dosyasına yerleştirilen katmanın sürümünü alır, genellikle 3. |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints/) { get; set; } | PSD dosyasındaki yerleştirilmiş katmanın yatay ağ noktalarını alır veya ayarlar. |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit/) { get; set; } | Dikey ağ noktalarının ölçü birimini alır veya ayarlar. |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder/) { get; set; } | PSD dosyasındaki yerleştirilmiş katmanın V sıra değerini alır veya ayarlar. |
| [Width](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/width/) { get; set; } | Genişliği alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/save/)(StreamContainer, int) | Akıllı nesne kaynağını belirtilen akış kapsayıcısına kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | a döndürürString bu örneği temsil eder. |

### Örnekler

Aşağıdaki kod, SoLEResource, SmartObjectResource ve PlacedResource kaynaklarının desteğini gösterir.

```csharp
[C#]

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}

void AssertAreEqual(object actual, object expected)
{
    var areEqual = object.Equals(actual, expected);
    if (!areEqual && actual is Array && expected is Array)
    {
        var actualArray = (Array)actual;
        var expectedArray = (Array)actual;
        if (actualArray.Length == expectedArray.Length)
        {
            for (int i = 0; i < actualArray.Length; i++)
            {
                if (!object.Equals(actualArray.GetValue(i), expectedArray.GetValue(i)))
                {
                    break;
                }
            }

            areEqual = true;
        }
    }

    if (!areEqual)
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

void CheckSmartObjectResourceValues(object[] expectedValue, SmartObjectResource resource)
{
    AssertAreEqual(expectedValue[0], resource.IsCustom);
    AssertAreEqual(expectedValue[2], resource.PageNumber);
    AssertAreEqual(expectedValue[3], resource.TotalPages);
    AssertAreEqual(expectedValue[4], resource.AntiAliasPolicy);
    AssertAreEqual(expectedValue[5], resource.PlacedLayerType);
    AssertAreEqual(8, resource.TransformMatrix.Length);
    AssertAreEqual((double[])expectedValue[6], resource.TransformMatrix);
    AssertAreEqual(expectedValue[7], resource.Value);
    AssertAreEqual(expectedValue[8], resource.Perspective);
    AssertAreEqual(expectedValue[9], resource.PerspectiveOther);
    AssertAreEqual(expectedValue[10], resource.Top);
    AssertAreEqual(expectedValue[11], resource.Left);
    AssertAreEqual(expectedValue[12], resource.Bottom);
    AssertAreEqual(expectedValue[13], resource.Right);
    AssertAreEqual(expectedValue[14], resource.UOrder);
    AssertAreEqual(expectedValue[15], resource.VOrder);

    AssertAreEqual(expectedValue[16], resource.Crop);
    AssertAreEqual(expectedValue[17], resource.FrameStepNumerator);
    AssertAreEqual(expectedValue[18], resource.FrameStepDenominator);
    AssertAreEqual(expectedValue[19], resource.DurationNumerator);
    AssertAreEqual(expectedValue[20], resource.DurationDenominator);
    AssertAreEqual(expectedValue[21], resource.FrameCount);
    AssertAreEqual(expectedValue[22], resource.Width);
    AssertAreEqual(expectedValue[23], resource.Height);
    AssertAreEqual(expectedValue[24], resource.Resolution);
    AssertAreEqual(expectedValue[25], resource.ResolutionUnit);
    AssertAreEqual(expectedValue[26], resource.Comp);
    AssertAreEqual(expectedValue[27], resource.CompId);
    AssertAreEqual(expectedValue[28], resource.OriginalCompId);
    AssertAreEqual(expectedValue[29], resource.PlacedId.ToString());
    AssertAreEqual(expectedValue[30], resource.NonAffineTransformMatrix);
    if (resource.IsCustom)
    {
        AssertAreEqual(expectedValue[31], resource.HorizontalMeshPointUnit);
        AssertAreEqual((double[])expectedValue[32], resource.HorizontalMeshPoints);
        AssertAreEqual(expectedValue[33], resource.VerticalMeshPointUnit);
        AssertAreEqual((double[])expectedValue[34], resource.VerticalMeshPoints);
    }
}

void SetNewSmartValues(SmartObjectResource resource, object[] newValues)
{
    // Kaynakta değiştirmediğimiz bu değerler
    newValues[0] = resource.IsCustom;
    newValues[1] = resource.UniqueId.ToString();
    newValues[5] = resource.PlacedLayerType;
    newValues[14] = resource.UOrder;
    newValues[15] = resource.VOrder;
    newValues[28] = resource.OriginalCompId;

    // Bu değerler PlLdResource'da (belirtilen UniqueId ile) de değiştirilmelidir.
    // ve bazılarının LinkDataSource'daki altı çizili akıllı nesneyle uyumlu olması gerekir
    resource.PageNumber = (int)newValues[2]; // 2;
    resource.TotalPages = (int)newValues[3]; // 3;
    resource.AntiAliasPolicy = (int)newValues[4]; // 0;
    resource.TransformMatrix = (double[])newValues[6];
    resource.Value = (double)newValues[7]; // 1.23456789;
    resource.Perspective = (double)newValues[8]; // 0,123456789;
    resource.PerspectiveOther = (double)newValues[9]; // 0,987654321;
    resource.Top = (double)newValues[10]; // -126;
    resource.Left = (double)newValues[11]; // -215;
    resource.Bottom = (double)newValues[12]; // 248;
    resource.Right = (double)newValues[13]; // 145;
    resource.Crop = (int)newValues[16]; // 5;
    resource.FrameStepNumerator = (int)newValues[17]; // 1;
    resource.FrameStepDenominator = (int)newValues[18]; // 601;
    resource.DurationNumerator = (int)newValues[19]; // 2;
    resource.DurationDenominator = (int)newValues[20]; // 602;
    resource.FrameCount = (int)newValues[21]; // 11;
    resource.Width = (double)newValues[22]; // 541;
    resource.Height = (double)newValues[23]; // 249;
    resource.Resolution = (double)newValues[24]; // 144;
    resource.ResolutionUnit = (UnitTypes)newValues[25];
    resource.Comp = (int)newValues[26]; // 21;
    resource.CompId = (int)newValues[27]; // 22;
    resource.NonAffineTransformMatrix = (double[])newValues[30];

    // Bu unique ID varsa referanslarda değiştirilmelidir.
    resource.PlacedId = new Guid((string)newValues[29]);  // "12345678-9abc-def0-9876-54321fecba98");
    if (resource.IsCustom)
    {
        resource.HorizontalMeshPointUnit = (UnitTypes)newValues[31];
        resource.HorizontalMeshPoints = (double[])newValues[32];
        resource.VerticalMeshPointUnit = (UnitTypes)newValues[33];
        resource.VerticalMeshPoints = (double[])newValues[34];
    }

    // Bazı parametrelere dikkat edin: kaydedilen görüntü Adobe® Photoshop® tarafından okunamaz hale gelebilir
    ////kaynak.UOrder = 6;
    ////kaynak.VOrder = 9;

    // Bunu değiştirmeyin, aksi takdirde serbest dönüşümü kullanamazsınız
    // veya altı çizili akıllı nesneyi vektör türüne değiştirin
    ////resource.PlacedLayerType = PlacedLayerType.Vector;

    // Bu benzersiz kimliğe sahip geçerli bir PlLdResource olmalıdır
    ////resource.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");
}

object[] newSmartValues = new object[]
{
    true,
    null,
    2,
    3,
    0,
    PlacedLayerType.ImageStack,
    new double[8]
    {
        12.937922786050663,
        19.419959734187131,
        2.85445817782261,
        1.0540625423957124,
        7.20861031651307,
        14.634102808208553,
        17.292074924741144,
        4
    },
    1.23456789,
    0.123456789,
    0.987654321,
    -126d,
    -215d,
    248d,
    145d,
    4,
    4,
    5,
    1,
    601,
    2,
    602,
    11,
    541d,
    249d,
    144d,
    UnitTypes.Percent,
    21,
    22,
    23,
    "12345678-9abc-def0-9876-54321fecba98",
    new double[8]
    {
        129.937922786050663,
        195.419959734187131,
        26.85445817782261,
        12.0540625423957124,
        72.20861031651307,
        147.634102808208553,
        175.292074924741144,
        42
    },
    UnitTypes.Points,
    new double[16]
    {
        0.01d, 103.33333333333433d, 206.66686666666666d, 310.02d,
        0.20d, 103.33333333333533d, 206.69666666666666d, 310.03d,
        30.06d, 103.33333333336333d, 206.66660666666666d, 310.04d,
        04.05d, 103.33333333373333d, 206.66666166666666d, 310.05d
    },
    UnitTypes.Distance,
    new double[16]
    {
        0.06d, 0.07d, 0.08d, 0.09d,
        49.066666666666664d, 49.266666666666664d, 49.566666666666664d, 49.766666666666664d,
        99.133333333333329d, 99.433333333333329d, 99.633333333333329d, 99.833333333333329d,
        140, 141, 142, 143,
    },
};

object[] expectedValues = new object[]
{
    new object[]
    {
        false,
        "5867318f-3174-9f41-abca-22f56a75247e",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            0, 0, 2, 0, 2, 2, 0, 2
        },
        0d,
        0d,
        0d,
        0d,
        0d,
        2d,
        2d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        2d,
        2d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "64b3997c-06e0-be40-a349-41acf397c897",
        new double[8]
        {
            0, 0, 2, 0, 2, 2, 0, 2
        },
    }
};

var sourceFilePath = "rgb8_2x2_linked.psd";
var outputPath = "rgb8_2x2_linked_output.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    SoLeResource soleResource = null;
    int index = 0;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            var resource = imageResource as SoLeResource;
            if (resource != null)
            {
                soleResource = resource;
                var expectedValue = (object[])expectedValues[index++];
                AssertAreEqual(expectedValue[1], resource.UniqueId.ToString());
                CheckSmartObjectResourceValues(expectedValue, resource);
                SetNewSmartValues(resource, newSmartValues);

                break;
            }
        }
    }

    AssertIsTrue(soleResource != null);
    image.Save(outputPath, new PsdOptions(image));
    using (PsdImage savedImage = (PsdImage)Image.Load(outputPath))
    {
        foreach (Layer imageLayer in savedImage.Layers)
        {
            foreach (var imageResource in imageLayer.Resources)
            {
                var resource = imageResource as SoLeResource;
                if (resource != null)
                {
                    CheckSmartObjectResourceValues(newSmartValues, resource);

                    break;
                }
            }
        }
    }
}
```

### Ayrıca bakınız

* class [SoLdResource](../soldresource/)
* class [SoLeResource](../soleresource/)
* class [PlacedResource](../placedresource/)
* interface [ISmartObjectLayerResource](../ismartobjectlayerresource/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* toplantı [Aspose.PSD](../../)


