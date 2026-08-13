---
title: "TimeLine.ApplyTo"
second_title: "Aspose.PSD for .NET API Referansı"
description: "TimeLine yöntemi. Mevcut zaman çizelgesi değerlerini giriş PsdImage'e uygular"
type: docs
weight: 90
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/timeline/applyto/
---
{{< psd/tize >}}
## TimeLine.ApplyTo method

Mevcut zaman çizelgesi değerlerini giriş [`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/)e uygular.

```csharp
public void ApplyTo(PsdImage psdImage)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| psdImage | PsdImage | psd görüntüsü. |

## Örnekler

TimeLine sınıfı, PsdImage'in zaman çizelgesini, çerçeve gecikmesini değiştirme veya belirli bir çerçevede katman durumunu düzenleme gibi yüksek seviyeli bir yetenek sağlar.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Çerçeve 1'in dispose yöntemini değiştir.
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Çerçeve 2'nin gecikmesini değiştir.
    timeLine.Frames[1].Delay = 15;

    // Çerçeve 2'de 'Layer 1' opaklığını değiştir.
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // 'Layer 1'i çerçeve 3'te sol-alt köşeye taşı.
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Yeni çerçeve ekler.
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Çerçeve 4'te 'Layer 1' katmanının blendMode'unu değiştir
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Değişiklikleri PsdImage örneğine geri uygula
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Ayrıca Bakınız

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* assembly [Aspose.PSD](../../../)


