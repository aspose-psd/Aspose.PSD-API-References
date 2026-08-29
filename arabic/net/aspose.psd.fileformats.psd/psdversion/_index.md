---
title: "تعداد PsdVersion"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "تعداد Aspose.PSD.FileFormats.Psd.PsdVersion. إصدار تنسيق الملف"
type: docs
weight: 4060
url: /ar/net/aspose.psd.fileformats.psd/psdversion/
---
{{< psd/tize >}}
## PsdVersion enumeration

إصدار تنسيق الملف

```csharp
public enum PsdVersion : byte
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Psd | `1` | إصدار PSD الافتراضي. |
| Psb | `2` | إصدار PSB. |

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

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


