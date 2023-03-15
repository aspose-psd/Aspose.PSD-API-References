---
title: Image.Resize
second_title: Aspose.PSD for .NET API Referansı
description: Image yöntem. Görüntüyü yeniden boyutlandırır.
type: docs
weight: 190
url: /tr/net/aspose.psd/image/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Görüntüyü yeniden boyutlandırır.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |
| resizeType | ResizeType | Yeniden boyutlandırma türü. |

### Ayrıca bakınız

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* ad alanı [Aspose.PSD](../../image/)
* toplantı [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

Görüntüyü yeniden boyutlandırır. VarsayılanLeftTopToLeftTopkullanılır.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |

### Örnekler

Aşağıdaki örnek, PSD görüntüsünün nasıl yeniden boyutlandırılacağını ve Aspose.PSD ile elde ettiğimiz sonucu göstermektedir.

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ayrıca bakınız

* class [Image](../)
* ad alanı [Aspose.PSD](../../image/)
* toplantı [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Görüntüyü yeniden boyutlandırır.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |
| settings | ImageResizeSettings | Yeniden boyutlandırma ayarları. |

### Ayrıca bakınız

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* ad alanı [Aspose.PSD](../../image/)
* toplantı [Aspose.PSD](../../../)


