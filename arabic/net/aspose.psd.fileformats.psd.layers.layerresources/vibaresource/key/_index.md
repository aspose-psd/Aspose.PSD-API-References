---
title: VibAResource.Key
second_title: Aspose.PSD لمرجع .NET API
description: VibAResource ملكية. يحصل على مفتاح مورد الطبقة.
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/key/
---
## VibAResource.Key property

يحصل على مفتاح مورد الطبقة.

```csharp
public override int Key { get; }
```

### أمثلة

يوضح المثال التالي من التعليمات البرمجية دعم مورد VibAResource.

```csharp
[C#]

// مثال على دعم قراءة وكتابة مورد الاهتزاز في وقت التشغيل.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### أنظر أيضا

* class [VibAResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* المجسم [Aspose.PSD](../../../)


