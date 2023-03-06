---
title: Class DropShadowEffect
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect klass. Drop Shadow Layer effekt
type: docs
weight: 2120
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
## DropShadowEffect class

Drop Shadow Layer effekt

```csharp
public class DropShadowEffect : IShadowEffect
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | Hämtar eller ställer in vinkeln i grader. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | Hämtar eller ställer in blandningsläget. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | Hämtar eller ställer in färgen. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | Hämtar eller ställer in avståndet i pixlar. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | Får en typ av effekt |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | Hämtar eller ställer in ett värde som anger om denna instans är synlig. |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | Hämtar eller ställer in ett värde som anger om [slår ut]. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | Får eller ställer in bruset. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | Hämtar eller ställer in opaciteten. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | Hämtar eller ställer in oskärpa värdet i pixlar. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | Hämtar eller ställer in intensiteten som en procent. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | Hämtar eller ställer in ett värde som anger om [använd denna vinkel i alla lagereffekter]. |

### Exempel

Följande kod visar stöd för egenskapen PsdImage.GlobalAngle för att ändra det globala vinkelvärdet.

```csharp
[C#]

// När egenskapen DropShadowEffect.UseGlobalLight är 'true' använder DropShadowEffect-objektet vinkelvärdet från egenskapen PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

Följande kod visar hur Opacity-egenskapen för DropShadowEffect används.

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

    // Exempel med Opacitet = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Exempel med Opacitet = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Se även

* interface [IShadowEffect](../ishadoweffect/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* hopsättning [Aspose.PSD](../../)


