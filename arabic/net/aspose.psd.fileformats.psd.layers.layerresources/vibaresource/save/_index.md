---
title: VibAResource.Save
second_title: Aspose.PSD لمرجع .NET API
description: VibAResource طريقة. يحفظ المورد في حاوية التدفق المحددة.
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
## VibAResource.Save method

يحفظ المورد في حاوية التدفق المحددة.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| streamContainer | StreamContainer | حاوية التدفق للحفظ فيها. |
| psdVersion | Int32 | إصدار PSD. |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* المجسم [Aspose.PSD](../../../)


