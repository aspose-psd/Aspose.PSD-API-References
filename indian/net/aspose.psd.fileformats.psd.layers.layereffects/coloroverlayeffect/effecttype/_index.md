---
title: "ColorOverlayEffect.EffectType"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ColorOverlayEffect प्रॉपर्टी। प्राप्त करता है इफ़ेक्ट का प्रकार"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/effecttype/
---
{{< psd/tize >}}
## ColorOverlayEffect.EffectType property

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
* class [ColorOverlayEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


