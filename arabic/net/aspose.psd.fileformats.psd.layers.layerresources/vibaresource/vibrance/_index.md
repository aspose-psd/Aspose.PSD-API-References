---
title: "VibAResource.Vibrance"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "VibAResource خاصية. يحصل أو يضبط قيمة الإشراق"
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibrance/
---
{{< psd/tize >}}
## VibAResource.Vibrance property

يحصل أو يعيّن قيمة الحيوية

```csharp
public int Vibrance { get; set; }
```

## أمثلة

يوضح مثال الشيفرة التالي دعم مورد VibAResource.

```csharp
[C#]

// مثال على دعم قراءة وكتابة مورد الاهتزاز أثناء التشغيل.
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

### انظر أيضًا

* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


