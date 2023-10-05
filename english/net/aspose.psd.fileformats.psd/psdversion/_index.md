---
title: Enum PsdVersion
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.PsdVersion enum. File format version
type: docs
weight: 3790
url: /net/aspose.psd.fileformats.psd/psdversion/
---
{{< psd/tize >}}
## PsdVersion enumeration

File format version

```csharp
public enum PsdVersion : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Psd | `1` | The default PSD version. |
| Psb | `2` | The PSB version. |

## Examples

The following example shows ability to convert PSD file to PSB and vice versa.

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

### See Also

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


