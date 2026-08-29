---
title: "ILayerEffect.GetEffectBounds"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة ILayerEffect. تحسب وتحصل على حدود بكسلات التأثير بناءً على حدود بكسلات الطبقة المدخلة"
type: docs
weight: 50
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

احسب واحصل على حدود بكسلات التأثير بناءً على حدود بكسلات الطبقة المدخلة.

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| layerBounds | Rectangle | حدود بكسلات الطبقة. |
| globalAngle | Int32 | الزاوية العامة لحساب زاوية الضوء العامة. |

### قيمة الإرجاع

حدود بكسلات التأثير بناءً على حدود بكسلات الطبقة المدخلة.

## أمثلة

يوضح كيفية الحصول على حدود الطبقة مع التأثيرات وتصديرها بالحجم الصحيح.

```csharp
[C#]

string srcFile = "1958.psd";
string outputFile = "out_1958.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    var layer1 = psdImage.Layers[1];

    var layerBoudns = layer1.Bounds;
    foreach (var effect in layer1.BlendingOptions.Effects)
    {
        layerBoudns = Rectangle.Union(
            layerBoudns,
            effect.GetEffectBounds(layer1.Bounds, psdImage.GlobalAngle));
    }

    Rectangle boundsToExport = Rectangle.Empty; // The default value is to save only the layer with effects.
                                                // boundsToExport = psdImage.Bounds; // لحفظ ضمن حدود PsdImage في موقع الطبقة الأصلي

    layer1.Save(
        outputFile,
        new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha },
        boundsToExport);

    using (var imgStream = new FileStream(outputFile, FileMode.Open))
    {
        var loadedLayer = new Layer(imgStream);
        if (loadedLayer.Size == layerBoudns.Size)
        {
            System.Console.WriteLine("The size is calculated correctly.");
        }
    }
}
```

### انظر أيضًا

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


