---
title: Enum PsdVersion
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.PsdVersion تعداد. إصدار تنسيق الملف
type: docs
weight: 3600
url: /ar/net/aspose.psd.fileformats.psd/psdversion/
---
## PsdVersion enumeration

إصدار تنسيق الملف

```csharp
public enum PsdVersion : byte
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| Psd | `1` | إصدار PSD الافتراضي . |
| Psb | `2` | إصدار PSB . |

### أمثلة

يوضح المثال التالي القدرة على تحويل ملف PSD إلى PSB والعكس صحيح.

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

### أنظر أيضا

* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* المجسم [Aspose.PSD](../../)


