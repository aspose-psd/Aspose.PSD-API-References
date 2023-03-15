---
title: Graphics.DrawString
second_title: Aspose.PSD for .NET API Referansı
description: Graphics yöntem. Belirtilen metin dizesini belirtilen konumda belirtilen konumla çizer.Brush VeFont nesneler.
type: docs
weight: 320
url: /tr/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Belirtilen metin dizesini belirtilen konumda belirtilen konumla çizer.[`Brush`](../../brush/) Ve[`Font`](../../font/) nesneler.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| s | String | Çizilecek dize. |
| font | Font | [`Font`](../../font/) bu, dizenin metin biçimini tanımlar. |
| brush | Brush | [`Brush`](../../brush/) çizilen metnin rengini ve dokusunu belirler. |
| x | Single | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | Single | Çizilen metnin sol üst köşesinin y koordinatı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *brush* null. -veya- *s* boş. |

### Ayrıca bakınız

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Belirtilen metin dizesini belirtilen konumda belirtilen konumla çizer.[`Brush`](../../brush/) Ve[`Font`](../../font/) nesneler.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| s | String | Çizilecek dize. |
| font | Font | [`Font`](../../font/) bu, dizenin metin biçimini tanımlar. |
| brush | Brush | [`Brush`](../../brush/) çizilen metnin rengini ve dokusunu belirler. |
| point | PointF | [`PointF`](../../pointf/) çizilen metnin sol üst köşesini belirten yapı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *brush* null. -veya- *s* boş. |

### Örnekler

Bu örnek, Image yüzeyinde dizeler çizmek için Font ve SolidBrush sınıfının kullanımını gösterir. Örnek, yeni bir Görüntü oluşturur ve Figures ve GraphicsPath kullanarak şekiller çizer.

```csharp
[C#]

//Görüntünün bir örneğini oluşturur
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics sınıfının bir örneğini oluşturur ve başlatır
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Grafik yüzeyini temizler
    graphics.Clear(Color.Wheat);

    // Font örneğini oluşturur
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Kırmızı Rengi olan bir SolidBrush örneği oluştur
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Bir Dizi Çiz
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // dışa aktarma seçeneklerini oluşturun.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // tüm değişiklikleri kaydet
    image.Save("C:\\temp\\output.gif", options);
}
```

### Ayrıca bakınız

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Belirtilen metin dizesini belirtilen konumda belirtilen konumla çizer.[`Brush`](../../brush/) Ve[`Font`](../../font/) belirtilen biçimlendirme özniteliklerini kullanan nesneler[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| s | String | Çizilecek dize. |
| font | Font | [`Font`](../../font/) bu, dizenin metin biçimini tanımlar. |
| brush | Brush | [`Brush`](../../brush/) çizilen metnin rengini ve dokusunu belirler. |
| x | Single | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | Single | Çizilen metnin sol üst köşesinin y koordinatı. |
| format | StringFormat | [`StringFormat`](../../stringformat/) çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme niteliklerini belirtir. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *brush* null. -veya- *s* boş. |

### Ayrıca bakınız

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Belirtilen metin dizesini belirtilen konumda belirtilen konumla çizer.[`Brush`](../../brush/) Ve[`Font`](../../font/) belirtilen biçimlendirme özniteliklerini kullanan nesneler[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| s | String | Çizilecek dize. |
| font | Font | [`Font`](../../font/) bu, dizenin metin biçimini tanımlar. |
| brush | Brush | [`Brush`](../../brush/) çizilen metnin rengini ve dokusunu belirler. |
| point | PointF | [`PointF`](../../pointf/) çizilen metnin sol üst köşesini belirten yapı. |
| format | StringFormat | [`StringFormat`](../../stringformat/) çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme niteliklerini belirtir. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *brush* null. -veya- *s* boş. |

### Ayrıca bakınız

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Belirtilen metin dizesini, belirtilen dikdörtgene belirtilen değerle çizer.[`Brush`](../../brush/) Ve[`Font`](../../font/) nesneler.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| s | String | Çizilecek dize. |
| font | Font | [`Font`](../../font/) bu, dizenin metin biçimini tanımlar. |
| brush | Brush | [`Brush`](../../brush/) çizilen metnin rengini ve dokusunu belirler. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) çizilen metnin konumunu belirten yapı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *brush* null. -veya- *s* boş. |

### Ayrıca bakınız

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Belirtilen metin dizesini, belirtilen dikdörtgene belirtilen değerle çizer.[`Brush`](../../brush/) Ve[`Font`](../../font/) belirtilen biçimlendirme özniteliklerini kullanan nesneler[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| s | String | Çizilecek dize. |
| font | Font | [`Font`](../../font/) bu, dizenin metin biçimini tanımlar. |
| brush | Brush | [`Brush`](../../brush/) çizilen metnin rengini ve dokusunu belirler. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) çizilen metnin konumunu belirten yapı. |
| format | StringFormat | [`StringFormat`](../../stringformat/) çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme niteliklerini belirtir. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *brush* null. -veya- *s* null. -veya- *brush* boş. |

### Ayrıca bakınız

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)


