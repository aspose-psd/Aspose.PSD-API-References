---
title: "PsdLoadOptions.AllowWarpRepaint"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية PsdLoadOptions. تحصل أو تعين ما إذا كان سيتم الحفظ مع الصورة المرسومة مع أو بدون تحويل التشويه"
type: docs
weight: 30
url: /ar/net/aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowWarpRepaint property

يحصل أو يعيّن ما إذا كان يجب الحفظ مع الصورة المرسومة، مع أو بدون تحويل التشويه.

```csharp
public bool AllowWarpRepaint { get; set; }
```

### Property Value

`true` رَسْم الصورة مع تحويل التشويه `false`.

## أمثلة

الكود التالي يوضح عرض تأثير الالتواء.

```csharp
[C#]

string sourceFile = "source.psd";
string pngWarpedExport = "warped.png";
string psdWarpedExport = "warpFile.psd";

var warpLoadOptions = new PsdLoadOptions() { AllowWarpRepaint = true };

using (var image = (PsdImage)Image.Load(sourceFile, warpLoadOptions))
{
    image.Save(pngWarpedExport, new PngOptions());
    image.Save(psdWarpedExport, new PsdOptions());
}
```

### انظر أيضًا

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


