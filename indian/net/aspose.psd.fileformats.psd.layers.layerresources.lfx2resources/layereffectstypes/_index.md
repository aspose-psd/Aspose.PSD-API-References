---
title: "Enum LayerEffectsTypes"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes enum. लेयर ब्लेंडिंग इफ़ेक्ट्स"
type: docs
weight: 2900
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

लेयर ब्लेंडिंग प्रभाव।

```csharp
public enum LayerEffectsTypes
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| DropShadow | `0` | यह ड्रॉप शैडो। |
| OuterGlow | `1` | यह आउटेर ग्लो। |
| PatternOverlay | `2` | यह पैटर्न ओवरले। |
| GradientOverlay | `3` | यह ग्रेडिएंट ओवरले। |
| ColorOverlay | `4` | यह रंग ओवरले। |
| Satin | `5` | यह सैटिन इफ़ेक्ट टाइप। |
| InnerGlow | `6` | यह इनर ग्लो। |
| InnerShadow | `7` | यह इनर शैडो। |
| Stroke | `8` | यह स्ट्रोक। |
| BevelEmboss | `9` | यह बिवेल एम्बॉस। |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* assembly [Aspose.PSD](../../)


