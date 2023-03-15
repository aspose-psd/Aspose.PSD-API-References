---
title: SoCoResource.Color
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: SoCoResource संपत्त. आरजब रंग प्रप्त करत है .
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
## SoCoResource.Color property

आरजीबी रंग प्राप्त करता है .

```csharp
public Color Color { get; set; }
```

### प्रतिलाभ की मात्रा

आरजीबी रंग

### उदाहरण

निम्न उदाहरण प्रदर्शित करता है कि आप SoCoResource (रंग भरण परत के लिए परत संसाधन) को कैसे संपादित करते हैं

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // फिललेयर की खोज
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // लेयर रिसोर्स लिस्ट में SoCoResource का पता लगाना
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

                    // SoCoResource कलर प्रॉपर्टी सेट करना
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

### यह सभी देखें

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../socoresource/)
* सभा [Aspose.PSD](../../../)


