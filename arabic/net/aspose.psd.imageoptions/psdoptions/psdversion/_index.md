---
title: "PsdOptions.PsdVersion"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية PsdOptions. تحصل أو تعين نسخة تنسيق الملف. يمكن أن تكون PSD أو PSB"
type: docs
weight: 70
url: /ar/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
{{< psd/tize >}}
## PsdOptions.PsdVersion property

يحصل أو يضبط إصدار تنسيق الملف. يمكن أن يكون PSD أو PSB.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Property Value

نسخة تنسيق الملف.

## أمثلة

المثال التالي يوضح القدرة على تحويل ملف PSD إلى PSB والعكس.

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

### انظر أيضًا

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


