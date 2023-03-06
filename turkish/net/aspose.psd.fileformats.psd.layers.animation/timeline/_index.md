---
title: Class TimeLine
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.TimeLine sınıf. Zaman çizelgesi seçenekleri model.
type: docs
weight: 1880
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
## TimeLine class

Zaman çizelgesi seçenekleri model.

```csharp
public sealed class TimeLine
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [TimeLine](timeline/)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframe/) { get; set; } | Aktif çerçeve indeksini alır veya ayarlar. |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | AFSt değerini alır veya ayarlar. |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | Çerçeve listesini alır. |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | FsID değerini alır veya ayarlar. |
| [LayerIds](../../aspose.psd.fileformats.psd.layers.animation/timeline/layerids/) { get; set; } | Katman kimliği dizisini alır veya ayarlar. |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | Döngü sayısını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [InitializeFrom](../../aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/)(PsdImage) | Yeni örneğini oluşturur`TimeLine` , girişten başlatıldı[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |
| [ApplyTo](../../aspose.psd.fileformats.psd.layers.animation/timeline/applyto/)(PsdImage) | Girdiye geçerli zaman çizgisi değerlerini uygula[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |

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


