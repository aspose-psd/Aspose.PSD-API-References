---
title: "Enum PsdVersion"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.PsdVersion enum. ファイル形式のバージョン"
type: docs
weight: 4060
url: /ja/net/aspose.psd.fileformats.psd/psdversion/
---
{{< psd/tize >}}
## PsdVersion enumeration

ファイル形式バージョン

```csharp
public enum PsdVersion : byte
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Psd | `1` | デフォルトの PSD バージョンです。 |
| Psb | `2` | PSB バージョンです。 |

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

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


