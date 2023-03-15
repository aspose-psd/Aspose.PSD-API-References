---
title: Class DropShadowEffect
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect classe. Effet de calque dombre portée
type: docs
weight: 2120
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
## DropShadowEffect class

Effet de calque d'ombre portée

```csharp
public class DropShadowEffect : IShadowEffect
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | Obtient ou définit l'angle en degrés. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | Obtient ou définit le mode de fusion. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | Obtient ou définit la couleur. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | Obtient ou définit la distance en pixels. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | Obtient un type d'effet |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est visible. |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | Obtient ou définit une valeur indiquant si [knocks out]. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | Obtient ou définit le bruit. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | Obtient ou définit l'opacité. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | Obtient ou définit la valeur de flou en pixels. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | Obtient ou définit l'intensité sous forme de pourcentage. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | Obtient ou définit une valeur indiquant si [utiliser cet angle dans tous les effets de calque]. |

### Exemples

Le code suivant illustre la prise en charge de la propriété PsdImage.GlobalAngle pour modifier la valeur d'angle global.

```csharp
[C#]

// Lorsque la propriété DropShadowEffect.UseGlobalLight est 'true', alors l'objet DropShadowEffect utilise la valeur d'angle de la propriété PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

Le code suivant illustre l'utilisation de la propriété Opacity de DropShadowEffect.

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

    // Exemple avec Opacité = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Exemple avec Opacité = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Voir également

* interface [IShadowEffect](../ishadoweffect/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* Assemblée [Aspose.PSD](../../)


