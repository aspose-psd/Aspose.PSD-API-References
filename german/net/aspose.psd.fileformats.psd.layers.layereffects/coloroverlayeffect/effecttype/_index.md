---
title: ColorOverlayEffect.EffectType
second_title: Aspose.PSD für .NET-API-Referenz
description: ColorOverlayEffect eigendom. Ruft eine Art Effekt ab
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/effecttype/
---
## ColorOverlayEffect.EffectType property

Ruft eine Art Effekt ab

```csharp
public LayerEffectsTypes EffectType { get; }
```

### Beispiele

Der folgende Code demonstriert die Unterstützung der ILayerEffect.EffectType-Eigenschaft.

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
            // es hat gefangen
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Siehe auch

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* class [ColorOverlayEffect](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../coloroverlayeffect/)
* Montage [Aspose.PSD](../../../)


