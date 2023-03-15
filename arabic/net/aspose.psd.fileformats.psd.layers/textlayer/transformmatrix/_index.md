---
title: TextLayer.TransformMatrix
second_title: Aspose.PSD لمرجع .NET API
description: TextLayer ملكية. الحصول على مصفوفة التحويل أو تعيينها
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
## TextLayer.TransformMatrix property

الحصول على مصفوفة التحويل أو تعيينها

```csharp
public double[] TransformMatrix { get; set; }
```

### Property_Value

مصفوفة التحويل

### أمثلة

يوضح الكود التالي كيفية الحصول على حجم الخط لأي جزء نص في طبقة النص.

```csharp
[C#]

// استخرج حجم خط خاطئ 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // واجهة برمجة التطبيقات القديمة (باستخدام خط الفقرة الأولى)
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

    // واجهة برمجة تطبيقات جديدة (قد تحتوي طبقة نصية واحدة على أي كمية من أحجام الخطوط)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // التحقق من حجم خط الجزء الأساسي
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // التحقق من حجم خط الجزء الحقيقي
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### أنظر أيضا

* class [TextLayer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* المجسم [Aspose.PSD](../../../)


