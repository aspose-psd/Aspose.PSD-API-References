---
title: "WarpSettings.ProcessingArea"
second_title: "Aspose.PSD for .NET API 参考"
description: "WarpSettings 属性。获取或设置处理区域大小的值。默认值为 10。范围为 240。"
type: docs
weight: 40
url: /zh/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/
---
{{< psd/tize >}}
## WarpSettings.ProcessingArea property

获取或设置处理区域大小的值。默认值为 10。范围为 [2;40]

```csharp
public int ProcessingArea { get; set; }
```

## 示例

以下代码演示了 WarpSettings.ProcessingArea 属性用于配置扭曲变形。

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
        // 它从智能图层获取 WarpSettings
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // 它设置扭曲处理区域的大小
        warpSettings.ProcessingArea = areaValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + areaValues[i] + ".png";
        outputFiles.Add(outputFile);

        // 这里不应出现错误
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 另请参阅

* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


