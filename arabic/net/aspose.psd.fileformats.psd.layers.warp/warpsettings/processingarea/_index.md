---
title: "WarpSettings.ProcessingArea"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية WarpSettings. تحصل أو تعيين قيمة حجم منطقة المعالجة. القيمة الافتراضية هي 10. النطاق هو 240"
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/
---
{{< psd/tize >}}
## WarpSettings.ProcessingArea property

يحصل أو يضبط قيمة حجم منطقة المعالجة. القيمة الافتراضية هي 10. النطاق هو [2;40]

```csharp
public int ProcessingArea { get; set; }
```

## أمثلة

الكود التالي يوضح خاصية WarpSettings.ProcessingArea لتكوين تشوه الالتواء.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

int[] areaValues = { 5, 10, 25, 40 };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // يحصل على WarpSettings من الطبقة الذكية
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // يضبط حجم منطقة معالجة الالتواء
        warpSettings.ProcessingArea = areaValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + areaValues[i] + ".png";
        outputFiles.Add(outputFile);

        // يجب ألا يكون هناك أي خطأ هنا
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### انظر أيضًا

* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


