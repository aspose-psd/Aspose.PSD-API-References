---
title: "VibAResource.Key"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "VibAResource خاصية. يحصل على مفتاح مورد الطبقة"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/key/
---
{{< psd/tize >}}
## VibAResource.Key property

يحصل على مفتاح مورد الطبقة.

```csharp
public override int Key { get; }
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


