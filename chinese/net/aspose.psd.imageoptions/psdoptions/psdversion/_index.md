---
title: "PsdOptions.PsdVersion"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdOptions 属性。获取或设置文件格式版本。它可以是 PSD 或 PSB"
type: docs
weight: 70
url: /zh/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
{{< psd/tize >}}
## PsdOptions.PsdVersion property

获取或设置文件格式版本。它可以是 PSD 或 PSB。

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Property Value

文件格式版本。

## 示例

以下示例展示了将 PSD 文件转换为 PSB 以及反向转换的能力。

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

### 另请参阅

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


