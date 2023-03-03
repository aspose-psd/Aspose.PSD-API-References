---
title: Enum LayerEffectsTypes
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes एनुम. परत सम्मश्रण प्रभव
type: docs
weight: 2660
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
## LayerEffectsTypes enumeration

परत सम्मिश्रण प्रभाव।

```csharp
public enum LayerEffectsTypes
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| DropShadow | `0` | ड्रॉप शैडो. |
| OuterGlow | `1` | बाहरी चमक। |
| PatternOverlay | `2` | पैटर्न ओवरले. |
| GradientOverlay | `3` | ग्रेडिएंट ओवरले. |
| ColorOverlay | `4` | रंग ओवरले. |
| Satin | `5` | साटन प्रभाव प्रकार। |
| InnerGlow | `6` | आंतरिक चमक। |
| InnerShadow | `7` | आंतरिक छाया। |
| Stroke | `8` | स्ट्रोक। |
| BevelEmboss | `9` | बेवेल एम्बॉस. |

### उदाहरण

निम्नलिखित कोड ILayerEffect.EffectType संपत्ति के समर्थन को प्रदर्शित करता है।

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

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* सभा [Aspose.PSD](../../)


