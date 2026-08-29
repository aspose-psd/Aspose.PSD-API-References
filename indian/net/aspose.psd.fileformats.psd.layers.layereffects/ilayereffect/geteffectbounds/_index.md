---
title: "ILayerEffect.GetEffectBounds"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ILayerEffect मेथड। इनपुट लेयर पिक्सेल सीमाओं के आधार पर इफ़ेक्ट पिक्सेल की सीमाओं की गणना करता है और प्राप्त करता है"
type: docs
weight: 50
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

इनपुट लेयर पिक्सेल सीमाओं के आधार पर इफ़ेक्ट पिक्सेल की सीमाओं की गणना करता है और प्राप्त करता है।

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| layerBounds | Rectangle | लेयर पिक्सेल की सीमाएँ। |
| globalAngle | Int32 | वैश्विक प्रकाश कोण की गणना के लिए वैश्विक कोण। |

### रिटर्न वैल्यू

इनपुट लेयर पिक्सेल सीमाओं के आधार पर प्रभाव पिक्सेल की सीमाएँ।

## उदाहरण

दिखाता है कि प्रभावों के साथ लेयर की सीमाएँ कैसे प्राप्त करें और सही आकार के साथ निर्यात करें।

```csharp
[C#]

string srcFile = "1958.psd";
string outputFile = "out_1958.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    var layer1 = psdImage.Layers[1];

    var layerBoudns = layer1.Bounds;
    foreach (var effect in layer1.BlendingOptions.Effects)
    {
        layerBoudns = Rectangle.Union(
            layerBoudns,
            effect.GetEffectBounds(layer1.Bounds, psdImage.GlobalAngle));
    }

    Rectangle boundsToExport = Rectangle.Empty; // The default value is to save only the layer with effects.
                                                // boundsToExport = psdImage.Bounds; // मूल लेयर स्थान पर PsdImage सीमाओं के भीतर सहेजने के लिए

    layer1.Save(
        outputFile,
        new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha },
        boundsToExport);

    using (var imgStream = new FileStream(outputFile, FileMode.Open))
    {
        var loadedLayer = new Layer(imgStream);
        if (loadedLayer.Size == layerBoudns.Size)
        {
            System.Console.WriteLine("The size is calculated correctly.");
        }
    }
}
```

### देखें भी

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


