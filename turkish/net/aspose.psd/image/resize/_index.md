---
title: "Image.Resize"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Image yöntemi. Görüntüyü yeniden boyutlandırır"
type: docs
weight: 200
url: /tr/net/aspose.psd/image/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

Görüntüyü yeniden boyutlandırır.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |
| resizeType | ResizeType | Yeniden boyutlandırma türü. |

### Ayrıca Bakınız

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

Görüntüyü yeniden boyutlandırır. Varsayılan NearestNeighbourResample kullanılır.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |

## Örnekler

Aşağıdaki örnek, PSD görüntüsünü nasıl yeniden boyutlandıracağımızı ve Aspose.PSD ile elde ettiğimiz sonucu gösterir

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName, new PsdLoadOptions() { LoadEffectsResource = true }) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ayrıca Bakınız

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Görüntüyü yeniden boyutlandırır.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |
| ayarlar | ImageResizeSettings | Yeniden boyutlandırma ayarları. |

### Ayrıca Bakınız

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


