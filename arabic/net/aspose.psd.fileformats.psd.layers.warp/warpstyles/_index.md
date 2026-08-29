---
title: "تعداد WarpStyles"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "تعداد Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles. أنواع أنماط الالتواء المدعومة"
type: docs
weight: 4020
url: /ar/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

أنواع أنماط التشويه المدعومة.

```csharp
public enum WarpStyles
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | `0` | يتم تعيين النمط عندما تكون الطبقة بدون تشوه |
| Custom | `1` | نمط مع حركة عشوائية للنقاط |
| Arc | `2` | نمط القوس للالتواء |
| ArcUpper | `3` | نمط القوس العلوي للالتواء |
| ArcLower | `4` | نمط القوس السفلي للالتواء |
| Arch | `5` | نمط القوس المقوس للالتواء |
| Bulge | `6` | نمط الانتفاخ للالتواء |
| Flag | `7` | نمط العلم للالتواء |
| Fish | `8` | نمط السمكة للالتواء |
| Rise | `9` | نمط الارتفاع للالتواء |
| Wave | `10` | نمط الموجة للالتواء |
| Twist | `11` | نوع الالتواء اللولبي |
| Squeeze | `12` | نوع الضغط للالتواء |
| Inflate | `13` | نوع التضخم للانحراف |

## أمثلة

الكود التالي يوضح كيفية تعديل WarpSettings لإجراء تحويل الالتواء على SmartObjectLayer و TexLayer.

```csharp
[C#]

string sourceFile = "smart_without_warp.psd";

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
    AllowWarpRepaint = true
};

string[] outputImageFile = new string[4];
string[] outputPsdFile = new string[4];

for (int caseIndex = 0; caseIndex < outputImageFile.Length; caseIndex++)
{
    outputImageFile[caseIndex] = "export_" + caseIndex + ".png";
    outputPsdFile[caseIndex] = "export_" + caseIndex + ".psd";

    using (PsdImage img = (PsdImage)Image.Load(sourceFile, opt))
    {
        foreach (Layer layer in img.Layers)
        {
            if (layer is SmartObjectLayer)
            {
                var smartLayer = (SmartObjectLayer)layer;
                smartLayer.WarpSettings = GetWarpSettingsByIndex(smartLayer.WarpSettings, caseIndex);
            }

            if (layer is TextLayer)
            {
                var textLayer = (TextLayer)layer;

                if (caseIndex != 3)
                {
                    textLayer.WarpSettings = GetWarpSettingsByIndex(textLayer.WarpSettings, caseIndex);
                }
            }
        }

        img.Save(outputPsdFile[caseIndex], new PsdOptions());
    }

    using (PsdImage img = (PsdImage)Image.Load(outputPsdFile[caseIndex], opt))
    {
        img.Save(outputImageFile[caseIndex],
            new PngOptions() { CompressionLevel = 9, ColorType = PngColorType.TruecolorWithAlpha });
    }
}

WarpSettings GetWarpSettingsByIndex(WarpSettings warpParams, int caseIndex)
{
    switch (caseIndex)
    {
        case 0:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 20;
            break;
        case 1:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Vertical;
            warpParams.Value = 10;
            break;
        case 2:
            warpParams.Style = WarpStyles.Flag;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 30;
            break;
        case 3:
            warpParams.Style = WarpStyles.Custom;
            warpParams.MeshPoints[2].Y += 70;
            break;
    }

    return warpParams;
}
```

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


