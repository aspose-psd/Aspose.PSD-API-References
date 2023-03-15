---
title: Class DropShadowEffect
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect classe. Effetto livello ombra esterna
type: docs
weight: 2120
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
## DropShadowEffect class

Effetto livello ombra esterna

```csharp
public class DropShadowEffect : IShadowEffect
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | Ottiene o imposta l'angolo in gradi. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | Ottiene o imposta la modalità di fusione. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | Ottiene o imposta il colore. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | Ottiene o imposta la distanza in pixel. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | Ottiene un tipo di effetto |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è visibile. |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | Ottiene o imposta un valore che indica se [knock out]. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | Ottiene o imposta il rumore. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | Ottiene o imposta l'opacità. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | Ottiene o imposta il valore di sfocatura in pixel. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | Ottiene o imposta l'intensità come percentuale. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | Ottiene o imposta un valore che indica se [utilizzare questo angolo in tutti gli effetti di livello]. |

### Esempi

Il codice seguente illustra il supporto per la proprietà PsdImage.GlobalAngle per modificare il valore dell'angolo globale.

```csharp
[C#]

// Quando la proprietà DropShadowEffect.UseGlobalLight è 'true', l'oggetto DropShadowEffect utilizza il valore dell'angolo dalla proprietà PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

Il codice seguente illustra l'utilizzo della proprietà Opacity di DropShadowEffect.

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

    // Esempio con Opacità = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Esempio con Opacità = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Guarda anche

* interface [IShadowEffect](../ishadoweffect/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assemblea [Aspose.PSD](../../)


