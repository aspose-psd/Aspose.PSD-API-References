---
title: "ITextStyle.IsStandardVerticalRomanAlignmentEnabled"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية ITextStyle. يحصل أو يضبط محاذاة الرومانية العمودية القياسية. هذا يعتمد على قيمة مورد BaselineDirection ويطبق فقط عندما يكون اتجاه النص عموديًا"
type: docs
weight: 170
url: /ar/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
{{< psd/tize >}}
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

يحصل أو يعيّن المحاذاة الرومانية العمودية القياسية. هذا يعتمد على قيمة مورد BaselineDirection ويطبق فقط عندما يكون اتجاه النص عموديًا.

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

## أمثلة

الكود التالي يوضح دعم الخاصية الجديدة IsStandardVerticalRomanAlignmentEnabled.

```csharp
[C#]

// الكود التالي يوضح القدرة على تعديل الخاصية الجديدة IsStandardVerticalRomanAlignmentEnabled.
// هذا لا يؤثر على العرض في الوقت الحالي، لكنه يسمح لك فقط بتعديل قيمة الخاصية.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // قراءة صحيحة
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }

    textPortion.Style.IsStandardVerticalRomanAlignmentEnabled = false;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (!textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // قراءة صحيحة
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### انظر أيضًا

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


