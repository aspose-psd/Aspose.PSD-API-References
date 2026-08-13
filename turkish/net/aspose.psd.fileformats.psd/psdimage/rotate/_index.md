---
title: "PsdImage.Rotate"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdImage yöntemi. Görüntüyü merkezin etrafında döndürür"
type: docs
weight: 670
url: /tr/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
{{< psd/tize >}}
## Rotate(float) {#rotate}

Görüntüyü merkezin etrafında döndür.

```csharp
public override void Rotate(float angle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | Single | Döndürme açısı derece cinsindendir. Pozitif değerler saat yönünde döndürür. |

## Örnekler

Aşağıdaki kod, görüntüyü belirli bir açı değeriyle döndürme yeteneğini gösterir.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Tüm görüntünün döndürülmesi
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Katmanın döndürülmesi
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Ayrıca Bakınız

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Görüntüyü merkezin etrafında döndür.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | Single | Döndürme açısı derece cinsindendir. Pozitif değerler saat yönünde döndürür. |
| resizeProportionally | Boolean | eğer `true` olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgenin (köşe noktaları) izdüşümlerine göre değişir; diğer durumda boyutlar dokunulmaz kalır ve yalnızca iç görüntü içeriği döndürülür. |
| backgroundColor | Renk | Arka planın rengi. |

### Ayrıca Bakınız

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


