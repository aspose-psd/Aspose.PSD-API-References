---
title: Enum PsdVersion
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.PsdVersion 列挙. ファイル形式 version
type: docs
weight: 3600
url: /ja/net/aspose.psd.fileformats.psd/psdversion/
---
## PsdVersion enumeration

ファイル形式 version

```csharp
public enum PsdVersion : byte
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| Psd | `1` | デフォルトの PSD バージョン。 |
| Psb | `2` | PSB バージョン。 |

### 例

次の例は、PSD ファイルを PSB に、またはその逆に変換する機能を示しています。

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

* 名前空間 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 組み立て [Aspose.PSD](../../)


