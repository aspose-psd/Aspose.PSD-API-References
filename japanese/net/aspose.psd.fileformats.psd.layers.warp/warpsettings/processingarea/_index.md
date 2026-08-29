---
title: "WarpSettings.ProcessingArea"
second_title: "Aspose.PSD for .NET API Reference"
description: "WarpSettings プロパティ。処理領域サイズの値を取得または設定します。デフォルト値は 10 です。範囲は 240 です。"
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/
---
{{< psd/tize >}}
## WarpSettings.ProcessingArea property

処理領域サイズの値を取得または設定します。デフォルト値は 10 です。範囲は [2;40] です。

```csharp
public int ProcessingArea { get; set; }
```

## 例

以下のコードは WarpSettings.ProcessingArea プロパティを使用してワープ変形を構成する方法を示しています。

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
        // Smart Layer から WarpSettings を取得します
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // ワープ処理領域のサイズを設定します
        warpSettings.ProcessingArea = areaValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + areaValues[i] + ".png";
        outputFiles.Add(outputFile);

        // ここにエラーはないはずです
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 関連項目

* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


