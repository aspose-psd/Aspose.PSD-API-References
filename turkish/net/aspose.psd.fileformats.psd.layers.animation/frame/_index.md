---
title: Class Frame
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame sınıf. Zaman çizelgesi çerçeve öğesi seçenekleri.
type: docs
weight: 1840
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
## Frame class

Zaman çizelgesi çerçeve öğesi seçenekleri.

```csharp
public sealed class Frame
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Frame](frame/)(TimeLine) | Yeni bir örneğini başlatır.`Frame` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | Çerçeve gecikme değerini centa-saniye cinsinden alır veya ayarlar. Örneğin, 1 saniyede 100 centa-saniye içerir. |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | frame. 'nin elden çıkarma yöntemini alır veya ayarlar |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | Çerçeve kimliğini alır veya ayarlar. |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; } | Gets ot, frame. 'nin katman durumlarını ayarlar. |

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

* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* toplantı [Aspose.PSD](../../)


