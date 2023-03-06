---
title: PsdImage.Rotate
second_title: Aspose.PSD for .NET API Referansı
description: PsdImage yöntem. Görüntüyü merkez etrafında döndürün.
type: docs
weight: 610
url: /tr/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
## Rotate(float) {#rotate}

Görüntüyü merkez etrafında döndürün.

```csharp
public override void Rotate(float angle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| angle | Single | Derece cinsinden döndürme açısı. Pozitif değerler saat yönünde dönecektir. |

### Örnekler

Aşağıdaki kod, görüntüyü belirli açı değerine göre döndürme yeteneğini gösterir.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Tüm görüntü döndürülüyor
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

// Katman döndürme
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

### Ayrıca bakınız

* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Görüntüyü merkez etrafında döndürün.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| angle | Single | Derece cinsinden döndürme açısı. Pozitif değerler saat yönünde dönecektir. |
| resizeProportionally | Boolean | olarak ayarlanmışsa`doğru` boyutlara dokunulmadığı ve yalnızca dahili görüntü içeriğinin döndürüldüğü diğer durumda, görüntü boyutunuzu döndürülmüş dikdörtgen (köşe noktaları) projeksiyonlarına göre değiştirmiş olacaksınız. |
| backgroundColor | Color | Arka plan rengi. |

### Ayrıca bakınız

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)


