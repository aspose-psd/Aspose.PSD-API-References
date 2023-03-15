---
title: ILayerEffect.EffectType
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: ILayerEffect संपत्त. एक प्रकर क प्रभव प्रप्त करत है
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/effecttype/
---
## ILayerEffect.EffectType property

एक प्रकार का प्रभाव प्राप्त करता है

```csharp
public LayerEffectsTypes EffectType { get; }
```

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

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* interface [ILayerEffect](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../ilayereffect/)
* सभा [Aspose.PSD](../../../)


