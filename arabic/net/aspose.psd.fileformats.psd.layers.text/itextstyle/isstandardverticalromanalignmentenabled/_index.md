---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: Aspose.PSD لمرجع .NET API
description: ITextStyle ملكية. الحصول على المحاذاة الرومانية الرأسية القياسية أو تعيينها.Vertical .
type: docs
weight: 170
url: /ar/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

الحصول على المحاذاة الرومانية الرأسية القياسية أو تعيينها.Vertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### أمثلة

توضح التعليمة البرمجية التالية دعم الخاصية IsStandardVerticalRomanAlignmentEnabled الجديدة.

```csharp
[C#]

// توضح التعليمات البرمجية التالية القدرة على تحرير خاصية IsStandardVerticalRomanAlignmentEnabled الجديدة.
// لا يؤثر هذا على العرض في الوقت الحالي ، ولكنه يسمح لك فقط بتحرير قيمة الخاصية.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // القراءة الصحيحة
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
        // القراءة الصحيحة
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### أنظر أيضا

* interface [ITextStyle](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* المجسم [Aspose.PSD](../../../)


