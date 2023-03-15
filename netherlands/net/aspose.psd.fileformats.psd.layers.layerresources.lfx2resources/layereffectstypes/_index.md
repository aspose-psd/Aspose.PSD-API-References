---
title: Enum LayerEffectsTypes
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes opsomming. Laagovervloeieffecten.
type: docs
weight: 2660
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
## LayerEffectsTypes enumeration

Laagovervloei-effecten.

```csharp
public enum LayerEffectsTypes
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| DropShadow | `0` | De slagschaduw. |
| OuterGlow | `1` | De buitenste gloed. |
| PatternOverlay | `2` | De patroonoverlay. |
| GradientOverlay | `3` | De verloopoverlay. |
| ColorOverlay | `4` | De kleuroverlay. |
| Satin | `5` | Het satijnen effecttype. |
| InnerGlow | `6` | De innerlijke gloed. |
| InnerShadow | `7` | De innerlijke schaduw. |
| Stroke | `8` | De slag. |
| BevelEmboss | `9` | De schuine reliëf. |

### Voorbeelden

De volgende code demonstreert de ondersteuning van de eigenschap ILayerEffect.EffectType.

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
            // het ving
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* montage [Aspose.PSD](../../)


