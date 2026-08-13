---
title: "Graphics.DrawString"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Graphics yöntemi. Belirtilen konumda, belirtilen Brush ve Font nesneleriyle belirtilen metin dizesini çizer."
type: docs
weight: 330
url: /tr/net/aspose.psd/graphics/drawstring/
---
{{< psd/tize >}}
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Belirtilen konumda, belirtilen [`Brush`](../../brush/) ve [`Font`](../../font/) nesneleriyle belirtilen metin dizesini çizer.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | String | Çizilecek dize. |
| font | Font | [`Font`](../../font/) dizenin metin biçimini tanımlar. |
| brush | Brush | [`Brush`](../../brush/) çizilen metnin renk ve dokusunu belirler. |
| x | Single | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | Single | Çizilen metnin sol üst köşesinin y koordinatı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null'dur. -or- *s* null'dur. |

### Ayrıca Bakınız

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Belirtilen konumda, belirtilen [`Brush`](../../brush/) ve [`Font`](../../font/) nesneleriyle belirtilen metin dizesini çizer.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | String | Çizilecek dize. |
| font | Font | [`Font`](../../font/) dizenin metin biçimini tanımlar. |
| brush | Brush | [`Brush`](../../brush/) çizilen metnin renk ve dokusunu belirler. |
| point | PointF | [`PointF`](../../pointf/) çizilen metnin sol üst köşesini belirten yapı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null'dur. -or- *s* null'dur. |

## Örnekler

Bu örnek, Font ve SolidBrush sınıfının Image yüzeyine metin çizmek için kullanımını gösterir. Örnek yeni bir Image oluşturur ve Figures ve GraphicsPath kullanarak şekiller çizer.

```csharp
[C#]

//Image sınıfının bir örneğini oluşturur
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics sınıfının bir örneğini oluşturur ve başlatır
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics yüzeyini temizler
    graphics.Clear(Color.Wheat);

    //Font sınıfının bir örneğini oluşturur
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Kırmızı renkli bir SolidBrush örneği oluşturur
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Bir dize çizer
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // dışa aktarma seçeneklerini oluştur.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // tüm değişiklikleri kaydet
    image.Save("C:\\temp\\output.gif", options);
}
```

### Ayrıca Bakınız

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Belirtilen konumda, belirtilen [`Brush`](../../brush/) ve [`Font`](../../font/) nesnelerini kullanarak, belirtilen [`StringFormat`](../../stringformat/) biçimlendirme özniteliklerini kullanarak, belirtilen metin dizesini çizer.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | String | Çizilecek dize. |
| font | Font | [`Font`](../../font/) dizenin metin biçimini tanımlar. |
| brush | Brush | [`Brush`](../../brush/) çizilen metnin renk ve dokusunu belirler. |
| x | Single | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | Single | Çizilen metnin sol üst köşesinin y koordinatı. |
| format | StringFormat | [`StringFormat`](../../stringformat/) çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özniteliklerini belirten. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null'dur. -or- *s* null'dur. |

### Ayrıca Bakınız

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Belirtilen konumda, belirtilen [`Brush`](../../brush/) ve [`Font`](../../font/) nesnelerini kullanarak, belirtilen [`StringFormat`](../../stringformat/) biçimlendirme özniteliklerini kullanarak, belirtilen metin dizesini çizer.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | String | Çizilecek dize. |
| font | Font | [`Font`](../../font/) dizenin metin biçimini tanımlar. |
| brush | Brush | [`Brush`](../../brush/) çizilen metnin renk ve dokusunu belirler. |
| point | PointF | [`PointF`](../../pointf/) çizilen metnin sol üst köşesini belirten yapı. |
| format | StringFormat | [`StringFormat`](../../stringformat/) çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özniteliklerini belirten. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null'dur. -or- *s* null'dur. |

### Ayrıca Bakınız

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Belirtilen [`Brush`](../../brush/) ve [`Font`](../../font/) nesnelerini kullanarak, belirtilen dikdörtgende belirtilen metin dizesini çizer.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | String | Çizilecek dize. |
| font | Font | [`Font`](../../font/) dizenin metin biçimini tanımlar. |
| brush | Brush | [`Brush`](../../brush/) çizilen metnin renk ve dokusunu belirler. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) çizilen metnin konumunu belirten yapı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null'dur. -or- *s* null'dur. |

### Ayrıca Bakınız

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Belirtilen [`Brush`](../../brush/) ve [`Font`](../../font/) nesnelerini, belirtilen [`StringFormat`](../../stringformat/) biçimlendirme özniteliklerini kullanarak, belirtilen dikdörtgende belirtilen metin dizesini çizer.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | String | Çizilecek dize. |
| font | Font | [`Font`](../../font/) dizenin metin biçimini tanımlar. |
| brush | Brush | [`Brush`](../../brush/) çizilen metnin renk ve dokusunu belirler. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) çizilen metnin konumunu belirten yapı. |
| format | StringFormat | [`StringFormat`](../../stringformat/) çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özniteliklerini belirten. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null'dur. -or- *s* null'dur. -or- *brush* null'dur. |

### Ayrıca Bakınız

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


