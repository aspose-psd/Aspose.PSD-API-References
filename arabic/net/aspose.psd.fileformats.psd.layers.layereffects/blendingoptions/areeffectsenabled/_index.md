---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية BlendingOptions. تحصل أو تعين رؤية جميع تأثيرات الطبقة"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

يحصل أو يضبط رؤية جميع تأثيرات الطبقة.

```csharp
public bool AreEffectsEnabled { get; set; }
```

## أمثلة

يوضح كيفية تمكين أو تعطيل تأثيرات الطبقة باستخدام خاصية AreEffectsEnabled.

```csharp
[C#]

string srcFile = "2485.psd";
string outputOnFile = "on_2485.png";
string outputOffFile = "off_2485.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Save(outputOnFile);

    psdImage.Layers[1].BlendingOptions.AreEffectsEnabled = false;

    psdImage.Save(outputOffFile);
}
```

### انظر أيضًا

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


