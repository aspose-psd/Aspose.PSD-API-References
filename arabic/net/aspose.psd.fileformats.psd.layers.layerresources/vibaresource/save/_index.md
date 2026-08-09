---
title: "VibAResource.Save"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "VibAResource طريقة. يحفظ المورد إلى حاوية الدفق المحددة"
type: docs
weight: 50
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
{{< psd/tize >}}
## VibAResource.Save method

يحفظ المورد في حاوية الدفق المحددة.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | StreamContainer | حاوية الدفق التي سيتم الحفظ فيها. |
| psdVersion | Int32 | إصدار PSD. |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


