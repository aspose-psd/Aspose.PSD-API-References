---
title: "PsdOptions.PsdVersion"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdOptions プロパティ。ファイル形式バージョンを取得または設定します。PSD または PSB にできます。"
type: docs
weight: 70
url: /ja/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
{{< psd/tize >}}
## PsdOptions.PsdVersion property

ファイル形式のバージョンを取得または設定します。PSD または PSB にできます。

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Property Value

ファイル形式バージョン。

## 例

以下の例は、PSD ファイルを PSB に、またはその逆に変換できることを示しています。

```csharp
[C#]

string sourceFilePathPsb = "2layers.psb";
string outputFilePathPsd = "ConvertFromPsb.psd";
using (Image img = Image.Load(sourceFilePathPsb))
{
    var options = new PsdOptions((PsdImage)img) { PsdVersion = PsdVersion.Psd };
    img.Save(outputFilePathPsd, options);
}

string sourceFilePathPsd = "2layers.psd";
string outputFilePathPsb = "ConvertFromPsd.psb";
using (Image img = Image.Load(sourceFilePathPsd))
{
    var options = new PsdOptions((PsdImage)img) { PsdVersion = PsdVersion.Psb };
    img.Save(outputFilePathPsb, options);
}
```

### 関連項目

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


