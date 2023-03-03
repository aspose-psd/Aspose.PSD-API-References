---
title: Layer.BlendModeKey
second_title: Aspose.PSD لمرجع .NET API
description: Layer ملكية. الحصول على أو تعيين مفتاح وضع المزج.
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.layers/layer/blendmodekey/
---
## Layer.BlendModeKey property

الحصول على أو تعيين مفتاح وضع المزج.

```csharp
public virtual BlendMode BlendModeKey { get; set; }
```

### Property_Value

مفتاح وضع المزج .

### أمثلة

يوضح المثال التالي كيف يمكنك استخدام وضع مزج طبقة PassThrough في Aspose.PSD

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### أنظر أيضا

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [Layer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* المجسم [Aspose.PSD](../../../)


