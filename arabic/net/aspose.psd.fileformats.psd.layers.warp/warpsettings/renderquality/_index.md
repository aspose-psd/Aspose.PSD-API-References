---
title: "WarpSettings.RenderQuality"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية WarpSettings. يحصل أو يضبط قيمة جودة عرض التشويه بين السرعة والجودة"
type: docs
weight: 50
url: /ar/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/
---
{{< psd/tize >}}
## WarpSettings.RenderQuality property

يحصل أو يضبط قيمة جودة عرض الانحراف - بين السرعة والجودة

```csharp
public RenderQuality RenderQuality { get; set; }
```

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

* enum [RenderQuality](../../renderquality/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


