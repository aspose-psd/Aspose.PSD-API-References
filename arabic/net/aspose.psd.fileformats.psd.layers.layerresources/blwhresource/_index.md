---
title: "الفئة BlwhResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BlwhResource. الفئة BlwhResource هي مورد لطبقة تعديل الأسود والأبيض"
type: docs
weight: 2580
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---
{{< psd/tize >}}
## BlwhResource class

الفئة BlwhResource هي مورد لطبقة تعديل الأسود والأبيض.

```csharp
public class BlwhResource : AdjustmentLayerResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [BlwhResource](blwhresource/)() | الباني الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BlackAndWhitePresetFileName](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/blackandwhitepresetfilename/) { get; set; } | يحصل أو يضبط اسم ملف الإعداد المسبق للونين الأسود والأبيض. |
| [Blues](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/blues/) { get; set; } | يحصل أو يضبط قيمة اللون الأزرق. |
| [BwPresetKind](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/bwpresetkind/) { get; set; } | يحصل أو يضبط قيمة نوع الإعداد المسبق للونين الأسود والأبيض. |
| [Cyans](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/cyans/) { get; set; } | يحصل أو يضبط قيمة اللون السيان. |
| [Greens](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/greens/) { get; set; } | يحصل أو يضبط قيمة اللون الأخضر. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/length/) { get; } | يحصل على طول مورد الطبقة بالبايت. |
| [Magentas](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/magentas/) { get; set; } | يحصل أو يضبط قيمة اللون الأرجواني. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| [Reds](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/reds/) { get; set; } | يحصل أو يضبط قيمة اللون الأحمر. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |
| [TintColor](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/tintcolor/) { get; set; } | يحصل أو يعيّن قيمة ARGB للون الصبغة. |
| [UseTint](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/usetint/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [tint color] مستخدمًا. |
| [Yellows](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/yellows/) { get; set; } | يحصل أو يضبط قيمة الأصفر. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية الدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

## أمثلة

المثال التالي يوضح كيفية تحرير BlwhResource.

```csharp
[C#]

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

const string ActualPropertyValueIsWrongMessage = "Expected property value is not equal to actual value";

string destinationFileName = "Output" + sourceFileName;
bool isRequiredResourceFound = false;
using (PsdImage im = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in im.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            if (layerResource is BlwhResource)
            {
                var blwhResource = (BlwhResource)layerResource;
                var blwhLayer = (BlackWhiteAdjustmentLayer)layer;
                isRequiredResourceFound = true;

                AssertIsTrue(blwhResource.Reds == reds, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Yellows == yellows, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Greens == greens, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Cyans == cyans, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Blues == blues, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Magentas == magentas, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.UseTint == useTint, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.TintColor == tintColor, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BwPresetKind == bwPresetKind, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BlackAndWhitePresetFileName == bwPresetFileName, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorRed - tintColorRed) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorGreen - tintColorGreen) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorBlue - tintColorBlue) < 1e-6, ActualPropertyValueIsWrongMessage);

                // اختبار التحرير والحفظ
                blwhResource.Reds = reds - 15;
                blwhResource.Yellows = yellows - 15;
                blwhResource.Greens = greens + 15;
                blwhResource.Cyans = cyans + 15;
                blwhResource.Blues = blues - 15;
                blwhResource.Magentas = magentas - 15;
                blwhResource.UseTint = !useTint;
                blwhResource.BwPresetKind = 4;
                blwhResource.BlackAndWhitePresetFileName = "bwPresetFileName";
                blwhLayer.TintColorRed = tintColorRed - 60;
                blwhLayer.TintColorGreen = tintColorGreen - 60;
                blwhLayer.TintColorBlue = tintColorBlue - 60;

                im.Save(destinationFileName);
                break;
            }
        }
    }
}

AssertIsTrue(isRequiredResourceFound, "The specified BlwhResource not found");

isRequiredResourceFound = false;

using (PsdImage im = (PsdImage)Image.Load(destinationFileName))
{
    foreach (var layer in im.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            if (layerResource is BlwhResource)
            {
                var blwhResource = (BlwhResource)layerResource;
                var blwhLayer = (BlackWhiteAdjustmentLayer)layer;
                isRequiredResourceFound = true;

                AssertIsTrue(blwhResource.Reds == reds - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Yellows == yellows - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Greens == greens + 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Cyans == cyans + 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Blues == blues - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Magentas == magentas - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.UseTint == !useTint, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.TintColor == newTintColor, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BwPresetKind == 4, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BlackAndWhitePresetFileName == "bwPresetFileName", ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorRed - tintColorRed + 60) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorGreen - tintColorGreen + 60) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorBlue - tintColorBlue + 60) < 1e-6, ActualPropertyValueIsWrongMessage);

                break;
            }
        }
    }
}

AssertIsTrue(isRequiredResourceFound, "The specified BlwhResource not found");
```

### انظر أيضًا

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


