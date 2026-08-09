---
title: "تعداد RenderQuality"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "تعداد Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality. يصف جودة عرض الالتواء"
type: docs
weight: 3990
url: /ar/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

يصف جودة عرض التشويه.

```csharp
public enum RenderQuality
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Turbo | `4` | الخيار الأسرع، لكن الجودة تتدهور. |
| VeryFast | `18` | إذا كنت تحتاجه بسرعة، قد يكون مناسبًا للانحناءات الصغيرة. |
| Fast | `35` | يسمح لك بجعل عملية العرض أسرع مع انخفاض بسيط في الجودة. |
| Normal | `60` | القيمة الموصى بها لمعظم الانحناءات |
| Good | `130` | جودة أعلى من القياسية، سرعة أبطأ. يوصى به للتشوهات القوية. |
| Excellent | `260` | الخيار الأبطأ. يوصى به للتشوهات القوية والدقة العالية. |

## أمثلة

الكود التالي يوضح خاصية WarpSettings.RenderQuality لتكوين تشوه الالتواء.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // يحصل على WarpSettings من الطبقة الذكية
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // يضبط حجم منطقة معالجة الالتواء
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // يجب ألا يكون هناك أي خطأ هنا
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


