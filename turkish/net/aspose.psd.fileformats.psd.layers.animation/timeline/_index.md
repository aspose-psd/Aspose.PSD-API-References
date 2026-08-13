---
title: "Sınıf Timeline"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.Timeline sınıfı. Zaman çizelgesi seçenekleri modeli"
type: docs
weight: 1980
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
{{< psd/tize >}}
## Timeline class

Zaman çizelgesi seçenekleri modeli.

```csharp
public sealed class Timeline
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Timeline](timeline/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ActiveFrameIndex](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/) { get; } | Etkin çerçeve indeksini alır. |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | AFSt değerini alır veya ayarlar. |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | Çerçevelerin listesini alır. |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | FsID değerini alır veya ayarlar. |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | Döngü sayısını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save)(Stream, ImageOptionsBase) | PsdImage ve Timeline verilerini, kaydetme seçeneklerine göre belirtilen formatta belirtilen akışa kaydeder. |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save_1)(string, ImageOptionsBase) | PsdImage ve Timeline verilerini, kaydetme seçeneklerine göre belirtilen formatta belirtilen dosya konumuna kaydeder. |
| [SwitchActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/)(int) | Etkin çerçeveyi hedeflenen çerçeveye değiştirir. |

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


