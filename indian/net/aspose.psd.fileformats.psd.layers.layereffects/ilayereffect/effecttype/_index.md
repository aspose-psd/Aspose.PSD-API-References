---
title: "ILayerEffect.EffectType"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ILayerEffect प्रॉपर्टी। इफ़ेक्ट का प्रकार प्राप्त करता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/effecttype/
---
{{< psd/tize >}}
## ILayerEffect.EffectType property

इफ़ेक्ट का प्रकार प्राप्त करता है।

```csharp
public LayerEffectsTypes EffectType { get; }
```

## उदाहरण

निम्नलिखित कोड ILayerEffect.EffectType प्रॉपर्टी के समर्थन को दर्शाता है।

```csharp
[C#]

string inputFile = "input.psd";
string outputWithout = "outputWithout.png";
string outputWith = "outputWith.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    psdImage.Save(outputWithout, new PngOptions());

    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;
    dropShadowEffect.Opacity = 20;

    foreach (ILayerEffect iEffect in workLayer.BlendingOptions.Effects)
    {
        if (iEffect.EffectType == LayerEffectsTypes.DropShadow)
        {
            // यह पकड़ा गया
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### देखें भी

* enum [LayerEffectsTypes](../../layereffectstypes/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


