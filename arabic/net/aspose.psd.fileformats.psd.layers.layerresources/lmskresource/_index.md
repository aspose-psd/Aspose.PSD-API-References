---
title: "الفئة LmskResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LmskResource. مورد LMsk"
type: docs
weight: 3020
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---
{{< psd/tize >}}
## LmskResource class

مورد LMsk.

```csharp
public class LmskResource : LayerResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [LmskResource](lmskresource/)() | ينشئ مثيلاً جديداً للفئة `LmskResource`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ColorComponent1](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent1/) { get; set; } | يحصل على المكوّن اللوني 1. |
| [ColorComponent2](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent2/) { get; set; } | يحصل على المكوّن اللوني 2. |
| [ColorComponent3](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent3/) { get; set; } | يحصل على المكوّن اللوني 3. |
| [ColorComponent4](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent4/) { get; set; } | يحصل على المكوّن اللوني 4. |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/) { get; set; } | يحصل على مساحة اللون. |
| [Flag](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/flag/) { get; } | يحصل على العلامة. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/length/) { get; } | يحصل على طول مورد الطبقة بالبايت. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/) { get; set; } | يحصل على الشفافية. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية الدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

## ملاحظات

يحتوي هذا المورد على معرف مساحة اللون، الذي يشير إلى نوع مساحة لون محدد، و4 مكوّنات لونية. اعتماداً على المعرف، تكون للمكوّنات اللونية معانٍ مختلفة. إذا كان نوع مساحة اللون لا يتطلب أربع قيم، فإن المكوّنات الإضافية تكون غير معرفة وتُكتب دائماً كصفر. المكوّنات اللونية حسب أنواع مساحات اللون: RGB - الثلاثة مكوّنات الأولى هي الأحمر، الأخضر، والأزرق. HSB - الثلاثة مكوّنات الأولى هي الصبغة، التشبع، والسطوع. CMYK - الأربع مكوّنات هي السيان، الماجنتا، الأصفر، والأسود. Lab - الثلاثة مكوّنات الأولى هي الإضاءة، a (الكرومينانس a)، و b (الكرومينانس b). Grayscale - المكوّن الأول هو قيمة الرمادي، من 0...10000.

## أمثلة

الكود التالي يوضح كيفية تغيير Layer Mask Display Options على صور 16‑بت من خلال تعديل خصائص LmskResource.

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// تحميل صورة 16-بت.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // العثور على LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // تحقق من خصائص LmskResource.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // تغيير خصائص LmskResource.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // حفظ الصورة.
    image.Save(outputPsd);
}
```

### انظر أيضًا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


