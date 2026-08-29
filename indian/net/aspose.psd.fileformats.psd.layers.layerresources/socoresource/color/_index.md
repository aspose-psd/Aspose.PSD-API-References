---
title: "SoCoResource.Color"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "SoCoResource प्रॉपर्टी। RGB रंग प्राप्त करता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
{{< psd/tize >}}
## SoCoResource.Color property

RGB रंग प्राप्त करता है।

```csharp
public Color Color { get; set; }
```

### रिटर्न वैल्यू

RGB रंग

## उदाहरण

निम्न उदाहरण दर्शाता है कि आप SoCoResource (Color Fill Layer के लिए लेयर रिसोर्स) को कैसे संपादित करते हैं

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // FillLayer की खोज
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // लेयर रिसोर्स सूची में SoCoResource की खोज
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // SoCoResource के Color प्रॉपर्टी को सेट करना
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### देखें भी

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


