---
title: "LayerState.Enabled"
second_title: "Aspose.PSD for .NET API Referansı"
description: "LayerState özelliği. Etkin durumunu alır veya ayarlar"
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/
---
{{< psd/tize >}}
## LayerState.Enabled property

Etkin durumunu alır veya ayarlar.

```csharp
public bool Enabled { get; set; }
```

## Örnekler

Timeline sınıfı, PsdImage zaman çizelgesini, çerçeve gecikmesini değiştirme veya belirli bir çerçevede katman durumunu düzenleme gibi yüksek seviyeli bir yetenek sağlar.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    // Çerçeve 1'in dispose yöntemini değiştir.
    timeline.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Çerçeve 2'nin gecikmesini değiştir.
    timeline.Frames[1].Delay = 15;

    // Çerçeve 2'de 'Layer 1' opaklığını değiştir.
    LayerState layerState11 = timeline.Frames[1].LayerStates[1];
    layerState11.Opacity = 50;

    // 'Layer 1'i çerçeve 3'te sol-alt köşeye taşı.
    LayerState layerState21 = timeline.Frames[2].LayerStates[1];
    layerState21.PositionOffset = new Point(-50, 230);

    // Yeni çerçeve ekler.
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    // Çerçeve 4'te 'Layer 1' katmanının blendMode'unu değiştir
    LayerState layerState31 = timeline.Frames[3].LayerStates[1];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Değişiklikleri PsdImage örneğine geri uygula
    psdImage.Save(outputPsd);
}
```

### Ayrıca Bakınız

* class [LayerState](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


