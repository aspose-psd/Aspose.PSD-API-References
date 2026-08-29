---
title: "Layer.ApplyLayerMask"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Layer. يطبق قناع الطبقة على الطبقة ثم يحذف القناع"
type: docs
weight: 350
url: /ar/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

يطبق قناع الطبقة على الطبقة، ثم يحذف القناع.

```csharp
public void ApplyLayerMask()
```

## أمثلة

الكود التالي يوضح الميزة لتطبيق القناع على الطبقة.

```csharp
[C#]

var sourceFile = "example.psd";
var outFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    psdImage.Layers[1].ApplyLayerMask();

    psdImage.Save(outFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### انظر أيضًا

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


