---
title: "Enum StrokePosition"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.StrokePosition enum. Konum ayarı, StrokeEffect içinde uygulandığı katmana göre çizginizin hizalanmasını kontrol eder."
type: docs
weight: 2400
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/
---
{{< psd/tize >}}
## StrokePosition enumeration

Konum ayarı, çizginizin uygulandığı katmana göre hizalanmasını [`StrokeEffect`](../strokeeffect/) içinde kontrol eder.

```csharp
public enum StrokePosition : short
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Inside | `0` | Çizgi, şeklin kenarından oluşturulacak ve nesnenin merkezine doğru içe doğru büyüyecek. |
| Center | `1` | Çizgi, şeklin kenarından oluşturulacak ve hem içe hem de dışa doğru büyüyecek. |
| Outside | `2` | Çizgi, şeklin kenarından oluşturulacak ve nesneden uzaklaşarak dışa doğru büyüyecek. |

## Örnekler

Bu örnek, Çizgi etkisini Renk, Gradyan veya Desen gibi farklı dolgu türleriyle ekleme yeteneğini gösterir.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. İç konumda Renk dolgu ekler
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. Dış konumda Renk dolgu ekler
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. Merkez konumda Renk dolgu ekler
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. İç konumda Gradyan dolgu ekler
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. Dış konumda Gradyan dolgu ekler
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. Merkez konumda Gradyan dolgu ekler
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. İç konumda Desen dolgu ekler
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. Dış konumda Desen dolgu ekler
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. Merkez konumda Desen dolgu ekler
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


