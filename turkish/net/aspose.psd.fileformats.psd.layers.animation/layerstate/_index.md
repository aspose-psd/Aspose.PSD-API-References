---
title: "Sınıf LayerState"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState sınıfı. Zaman çizelgesi katman durumunun seçenekleri."
type: docs
weight: 1960
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
{{< psd/tize >}}
## LayerState class

Zaman çizelgesi katman durumunun seçenekleri.

```csharp
public sealed class LayerState
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [LayerState](layerstate/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Karıştırma modunu alır veya ayarlar. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Etkin durumunu alır veya ayarlar. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Dolgu opaklık değerini alır veya ayarlar. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | HorizontalFXRf değerini alır veya ayarlar. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Katman kimliğini alır veya ayarlar. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Opaklık değerini alır veya ayarlar. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Gerçek katman konumuna ilişkin katman konum kaymasını alır veya ayarlar. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Katman durum etkilerini alır. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | VerticalFXRf değerini alır veya ayarlar. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


