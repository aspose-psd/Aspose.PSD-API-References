---
title: VibAResource.VibAResource
second_title: Aspose.PSD لمرجع .NET API
description: VibAResource البناء. يقوم بتهيئة مثيل جديد لملفVibAResource فئة .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibaresource/
---
## VibAResource constructor

يقوم بتهيئة مثيل جديد لملف[`VibAResource`](../) فئة .

```csharp
public VibAResource()
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


