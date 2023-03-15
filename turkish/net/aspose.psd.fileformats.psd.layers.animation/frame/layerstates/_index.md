---
title: Frame.LayerStates
second_title: Aspose.PSD for .NET API Referansı
description: Frame mülk. Gets ot frame. nin katman durumlarını ayarlar.
type: docs
weight: 50
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/frame/layerstates/
---
## Frame.LayerStates property

Gets ot, frame. 'nin katman durumlarını ayarlar.

```csharp
public Dictionary<int, LayerState> LayerStates { get; }
```

### Örnekler

TimeLine sınıfı, kare gecikmesini değiştirmek veya belirli bir karede katman durumunu düzenlemek gibi, PsdImage'ın zaman çizelgesini işlemek için üst düzey bir yetenek sağlar.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Çerçeve 1'in elden çıkarma yöntemini değiştir
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Çerçeve 2'nin gecikmesini değiştir
    timeLine.Frames[1].Delay = 15;

    // 2. karedeki 'Katman 1'in opaklığını değiştir
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // 'Katman 1'i 3. karede sol alt köşeye taşı
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Yeni çerçeve ekler
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // 4. karede "Katman 1"in blendMode'unu değiştir
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Değişiklikleri tekrar PsdImage örneğine uygula
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Ayrıca bakınız

* class [LayerState](../../layerstate/)
* class [Frame](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../frame/)
* toplantı [Aspose.PSD](../../../)


