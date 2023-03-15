---
title: PsdOptions.PsdVersion
second_title: Aspose.PSD لمرجع .NET API
description: PsdOptions ملكية. الحصول على إصدار تنسيق الملف أو تحديده. يمكن أن يكون PSD أو PSB.
type: docs
weight: 60
url: /ar/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
## PsdOptions.PsdVersion property

الحصول على إصدار تنسيق الملف أو تحديده. يمكن أن يكون PSD أو PSB.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Property_Value

إصدار تنسيق الملف .

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

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* مساحة الاسم [Aspose.PSD.ImageOptions](../../psdoptions/)
* المجسم [Aspose.PSD](../../../)


