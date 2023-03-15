---
title: Class DropShadowEffect
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect klas. Slagschaduwlaageffect
type: docs
weight: 2120
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
## DropShadowEffect class

Slagschaduwlaageffect

```csharp
public class DropShadowEffect : IShadowEffect
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | Haalt of stelt de hoek in graden in. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | Krijgt of stelt de overvloeimodus in. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | Krijgt of stelt de kleur in. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | Haalt of stelt de afstand in pixels in. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | Krijgt een type effect |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | Haalt of stelt een waarde in die aangeeft of deze instantie zichtbaar is. |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [knocks-out]. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | Krijgt of stelt de ruis in. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | Haalt of stelt de dekking in. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | Haalt of stelt de vervagingswaarde in pixels in. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | Haalt de intensiteit op of stelt deze in als een percentage. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of [deze hoek in alle laageffecten moet worden gebruikt]. |

### Voorbeelden

De volgende code demonstreert ondersteuning voor de eigenschap PsdImage.GlobalAngle om de globale hoekwaarde te wijzigen.

```csharp
[C#]

// Als de eigenschap DropShadowEffect.UseGlobalLight 'true' is, gebruikt het object DropShadowEffect de hoekwaarde van de eigenschap PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

De volgende code demonstreert het gebruik van de eigenschap Opacity van DropShadowEffect.

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // Voorbeeld met dekking = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Voorbeeld met dekking = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Zie ook

* interface [IShadowEffect](../ishadoweffect/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* montage [Aspose.PSD](../../)


