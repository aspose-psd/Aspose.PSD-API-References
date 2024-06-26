---
title: PsdOptions.PsdVersion
second_title: Aspose.PSD for .NET API Reference
description: PsdOptions property. Gets or sets the file format version. It can be PSD or PSB
type: docs
weight: 70
url: /net/aspose.psd.imageoptions/psdoptions/psdversion/
---
{{< psd/tize >}}
## PsdOptions.PsdVersion property

Gets or sets the file format version. It can be PSD or PSB.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Property Value

The file format version.

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

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


