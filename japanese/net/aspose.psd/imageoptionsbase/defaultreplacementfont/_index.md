---
title: "ImageOptionsBase.DefaultReplacementFont"
second_title: "Aspose.PSD for .NET API Reference"
description: "ImageOptionsBase プロパティ。ラスタへエクスポートする際に、PSD ファイル内の既存レイヤーフォントがシステムに存在しない場合にテキスト描画に使用されるデフォルト置換フォントを取得または設定します。デフォルトフォントの正しい名前を取得するには、次のコードスニペットを使用できます System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily families  col.Families string defaultFontName  families0.Name PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName"
type: docs
weight: 20
url: /ja/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
{{< psd/tize >}}
## ImageOptionsBase.DefaultReplacementFont property

デフォルトの置換フォントを取得または設定します（PSD ファイルの既存レイヤーフォントがシステムに存在しない場合に、ラスタにエクスポートするときにテキスト描画に使用されるフォント）。デフォルトフォント名を取得するには、次のコードスニペットを使用できます: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Property Value

デフォルト置換フォントです。

## 例

次の例は DefaultReplacementFont プロパティを使用してデフォルト置換フォントを変更する方法を示しています。

```csharp
[C#]

// Konstanting フォントはインストールしないでください。このテストはインストールされていないフォントを置換する必要があります。
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions() { AllowNonChangedLayerRepaint = true }))
{
    // この方法で、出力ごとに異なるフォントを使用できます。
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### 関連項目

* class [ImageOptionsBase](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


