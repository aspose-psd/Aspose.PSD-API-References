---
title: Class LayerState
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState sınıf. Zaman çizgisi katman durumu seçenekleri.
type: docs
weight: 1860
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
## LayerState class

Zaman çizgisi katman durumu seçenekleri.

```csharp
public sealed class LayerState
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [LayerState](layerstate/)(int) | Yeni bir örneğini başlatır.`LayerState` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Blen modunu alır veya ayarlar. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Etkin durumu alır veya ayarlar. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Dolgu opaklık değerini alır veya ayarlar. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | HorizontalFXRf değerini alır veya ayarlar. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Kimliği alır veya ayarlar. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Opaklık değerini alır veya ayarlar. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Gerçek katman konumuyla ilgili katman konumu ofsetini alır veya ayarlar. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Katman durumu efektlerini alır. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | VerticalFXRf değerini alır veya ayarlar. |

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


