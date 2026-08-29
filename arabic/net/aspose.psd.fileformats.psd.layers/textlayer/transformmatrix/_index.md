---
title: "TextLayer.TransformMatrix"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية TextLayer. يحصل أو يضبط مصفوفة التحويل"
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
{{< psd/tize >}}
## TextLayer.TransformMatrix property

يسترجع أو يعيّن مصفوفة التحويل

```csharp
public double[] TransformMatrix { get; set; }
```

### Property Value

مصفوفة التحويل

## أمثلة

الكود التالي يوضح كيفية الحصول على حجم الخط لأي جزء نص في طبقة النص.

```csharp
[C#]

// تم استخراج حجم خط غير صحيح 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // API القديم (باستخدام خط الفقرة الأولى)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // التحقق من حجم الخط الأساسي
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // التحقق من حجم الخط الحقيقي
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // واجهة برمجة تطبيقات جديدة (قد يحتوي طبقة نص واحدة على أي كمية من أحجام الخط)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // التحقق من حجم الخط للجزء الأساسي
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // التحقق من حجم الخط للجزء الحقيقي
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### انظر أيضًا

* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


