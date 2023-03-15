---
title: PsdOptions.PsdVersion
second_title: Aspose.PSD for .NET API リファレンス
description: PsdOptions 財産. ファイル形式のバージョンを取得または設定します PSD または PSB を指定できます
type: docs
weight: 60
url: /ja/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
## PsdOptions.PsdVersion property

ファイル形式のバージョンを取得または設定します。 PSD または PSB を指定できます。

```csharp
public PsdVersion PsdVersion { get; set; }
```

### プロパティ値

ファイル形式のバージョン。

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

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* 名前空間 [Aspose.PSD.ImageOptions](../../psdoptions/)
* 組み立て [Aspose.PSD](../../../)


