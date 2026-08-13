---
title: "LayerStateEffects.AddStroke"
second_title: "Aspose.PSD for .NET API Referansı"
description: "LayerStateEffects yöntemi. Çizgi etkisini ekler"
type: docs
weight: 90
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
{{< psd/tize >}}
## LayerStateEffects.AddStroke method

Kontur efektini ekler.

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillType | FillType | Çizgi doldurma türü. |

### Dönüş Değeri

Yeni [`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) sınıfı örneği.

## Örnekler

Aşağıdaki kod, Timeline çerçevelerindeki efekt desteğini gösterir.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    var layerStateEffects11 = timeline.Frames[1].LayerStates[1].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeline.Frames[2].LayerStates[1].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    psdImage.Save(outputFile);
}
```

### Ayrıca Bakınız

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


