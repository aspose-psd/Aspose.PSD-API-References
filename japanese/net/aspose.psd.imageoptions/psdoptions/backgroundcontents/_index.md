---
title: "PsdOptions.BackgroundContents"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdOptions プロパティ。背景色を取得または設定します。透明なオブジェクトの下で確認できます。"
type: docs
weight: 20
url: /ja/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

背景色を取得または設定します。透明オブジェクトの下で確認できます。

```csharp
public RawColor BackgroundContents { get; set; }
```

## 例

以下のコードは PsdOptions の BackgroundContents プロパティのサポートを示しています。

```csharp
[C#]

// psd ファイルのプレビューで半透明が正しく処理されません。
// BackgroundContents が White に割り当てられました。透明領域は白色になるはずです。

string sourceFile = "frog_nosymb.psd";
string outputFile = "frog_nosymb_backgroundcontents_output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    RawColor backgroundColor = new RawColor(PixelDataFormat.Rgb32Bpp);
    int argbValue = 255 << 24 | 255 << 16 | 255 << 8 | 255;
    backgroundColor.SetAsInt(argbValue); // White

    PsdOptions psdOptions = new PsdOptions(psdImage)
    {
        ColorMode = ColorModes.Rgb,
        CompressionMethod = CompressionMethod.RLE,
        ChannelsCount = 4,
        BackgroundContents = backgroundColor,
    };

    psdImage.Save(outputFile, psdOptions);
}
```

### 関連項目

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


