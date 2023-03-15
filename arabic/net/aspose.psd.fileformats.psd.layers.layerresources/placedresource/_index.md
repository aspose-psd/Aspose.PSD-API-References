---
title: Class PlacedResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PlacedResource فصل. يحدد فئة PlacedResource التي تحتوي على معلومات شائعة حول طبقة موضوعة أو طبقة كائن ذكي في ملف PSD. يتم استخدامه لدعم طبقات الكائنات الذكية في صور Adobe Photoshop .
type: docs
weight: 2940
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/
---
## PlacedResource class

يحدد فئة PlacedResource التي تحتوي على معلومات شائعة حول طبقة موضوعة أو طبقة كائن ذكي في ملف PSD. يتم استخدامه لدعم طبقات الكائنات الذكية في صور Adobe® Photoshop® .

```csharp
public abstract class PlacedResource : LayerResource, IPlacedLayerResource
```

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/antialiaspolicy/) { get; set; } | الحصول على أو تحديد سياسة الصقل للطبقة الموضوعة في صورة PSD. |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom/) { get; set; } | الحصول على أو تحديد الموقع السفلي للطبقة الموضوعة في صورة PSD. |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds/) { get; set; } | الحصول على أو تعيين حدود الطبقة الموضوعة في ملف PSD. |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints/) { get; set; } | الحصول على أو تعيين نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD. |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit/) { get; set; } | الحصول على أو تعيين وحدة قياس نقاط الشبكة الأفقية . |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom/) { get; set; } | الحصول على قيمة أو تعيينها للإشارة إلى ما إذا كان نمط التواء في المثيل مخصصًا أم لا. إذا تم الضبط على خطأ ، فإنه يمحو نقاط الشبكة. |
| virtual [Items](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/items/) { get; set; } | الحصول على أو تعيين عناصر الالتواء. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left/) { get; set; } | الحصول على أو تحديد الموقع الأيسر للطبقة الموضوعة في ملف PSD. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | الحصول على طول مورد الطبقة بالبايت. |
| virtual [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/pagenumber/) { get; set; } | الحصول على أو تحديد رقم الصفحة للطبقة الموضوعة في ملف PSD. |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective/) { get; set; } | الحصول على أو تعيين قيمة المنظور للطبقة الموضوعة في ملف PSD. |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother/) { get; set; } | الحصول على أو تحديد قيمة المنظور الأخرى للطبقة الموضوعة في ملف PSD. |
| virtual [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/placedlayertype/) { get; set; } | الحصول على أو تحديد نوع الطبقة الموضوعة في ملف PSD. |
| abstract [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى من إصدار psd المطلوب لمورد الطبقة. 0 يشير إلى عدم وجود قيود. |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right/) { get; set; } | الحصول على أو تحديد الموقع الصحيح للطبقة الموضوعة في ملف PSD. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/signature/) { get; } | الحصول على توقيع المورد الموضوع . |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top/) { get; set; } | الحصول على أو تحديد الموقع العلوي للطبقة الموضوعة في صورة PSD. |
| virtual [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/totalpages/) { get; set; } | الحصول على أو تعيين إجمالي صفحات الطبقة الموضوعة في ملف PSD. |
| virtual [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/transformmatrix/) { get; set; } | الحصول على أو تعيين مصفوفة التحويل للطبقة الموضوعة في ملف PSD. |
| virtual [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uniqueid/) { get; set; } | الحصول على أو تعيين المعرف الفريد العام للطبقة الموضوعة في صورة PSD. |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder/) { get; set; } | الحصول على أو تعيين قيمة طلب U للطبقة الموضوعة في ملف PSD. |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value/) { get; set; } | الحصول على أو تعيين قيمة التواء للطبقة الموضوعة في صورة PSD. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version/) { get; } | يحصل على نسخة الطبقة الموضوعة في ملف PSD ، عادة 3. |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints/) { get; set; } | الحصول على أو تعيين نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD. |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit/) { get; set; } | الحصول على أو تحديد وحدة قياس نقاط الشبكة العمودية. |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder/) { get; set; } | الحصول على أو تعيين قيمة ترتيب V للطبقة الموضوعة في ملف PSD. |

## طُرق

| اسم | وصف |
| --- | --- |
| abstract [Save](../../aspose.psd.fileformats.psd.layers/layerresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية التدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع أString الذي يمثل هذا المثال. |

### أمثلة

يوضح الكود التالي دعم موارد SoLEResource و SmartObjectResource و PlacedResource.

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
    // هذه القيم لا نغيرها في الموارد
    newValues[0] = resource.IsCustom;
    newValues[1] = resource.UniqueId.ToString();
    newValues[5] = resource.PlacedLayerType;
    newValues[14] = resource.UOrder;
    newValues[15] = resource.VOrder;
    newValues[28] = resource.OriginalCompId;

    // يجب تغيير هذه القيم في PlLdResource (مع UniqueId المحدد) أيضًا
    // ويجب أن يكون بعضها متوافقًا مع الكائن الذكي الذي تحته خط في LinkDataSource
    resource.PageNumber = (int)newValues[2]; // 2 ;
    resource.TotalPages = (int)newValues[3]; // 3 ;
    resource.AntiAliasPolicy = (int)newValues[4]; // 0 ;
    resource.TransformMatrix = (double[])newValues[6];
    resource.Value = (double)newValues[7]; // 1.23456789 ;
    resource.Perspective = (double)newValues[8]; // 0.123456789 ;
    resource.PerspectiveOther = (double)newValues[9]; // 0.987654321 ;
    resource.Top = (double)newValues[10]; // -126 ;
    resource.Left = (double)newValues[11]; // -215 ;
    resource.Bottom = (double)newValues[12]; // 248 ;
    resource.Right = (double)newValues[13]; // 145 ;
    resource.Crop = (int)newValues[16]; // 5 ;
    resource.FrameStepNumerator = (int)newValues[17]; // 1 ;
    resource.FrameStepDenominator = (int)newValues[18]; // 601 ;
    resource.DurationNumerator = (int)newValues[19]; // 2 ;
    resource.DurationDenominator = (int)newValues[20]; // 602 ;
    resource.FrameCount = (int)newValues[21]; // 11 ;
    resource.Width = (double)newValues[22]; // 541 ;
    resource.Height = (double)newValues[23]; // 249 ;
    resource.Resolution = (double)newValues[24]; // 144 ;
    resource.ResolutionUnit = (UnitTypes)newValues[25];
    resource.Comp = (int)newValues[26]; // 21 ;
    resource.CompId = (int)newValues[27]; // 22 ;
    resource.NonAffineTransformMatrix = (double[])newValues[30];

    // يجب تغيير هذا المعرف الفريد في المراجع إن وجدت
    resource.PlacedId = new Guid((string)newValues[29]);  // "12345678-9abc-def0-9876-54321fecba98") ;
    if (resource.IsCustom)
    {
        resource.HorizontalMeshPointUnit = (UnitTypes)newValues[31];
        resource.HorizontalMeshPoints = (double[])newValues[32];
        resource.VerticalMeshPointUnit = (UnitTypes)newValues[33];
        resource.VerticalMeshPoints = (double[])newValues[34];
    }

    // كن حذرًا مع بعض المعلمات: قد تصبح الصورة المحفوظة غير قابلة للقراءة بواسطة Adobe® Photoshop®
    ////resource.UOrder = 6 ;
    ////resource.VOrder = 9 ;

    // لا تقم بتغيير هذا وإلا فلن تتمكن من استخدام التحويل المجاني
    // أو قم بتغيير الكائن الذكي الذي تحته خط إلى نوع المتجه
    ////resource.PlacedLayerType = PlacedLayerType.Vector ;

    // يجب أن يكون هناك PlLdResource صالحًا بهذا المعرف الفريد
    ////resource.UniqueId = دليل جديد ("98765432-10fe-cba0-1234-56789abcdef0") ;
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

### أنظر أيضا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* interface [IPlacedLayerResource](../iplacedlayerresource/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* المجسم [Aspose.PSD](../../)


