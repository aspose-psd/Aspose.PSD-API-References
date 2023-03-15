---
title: Layer.Save
second_title: Aspose.PSD for .NET API Referansı
description: Layer yöntem. Nesnenin verilerini belirtilen akışa kaydeder.
type: docs
weight: 370
url: /tr/net/aspose.psd.fileformats.psd.layers/layer/save/
---
## Save(Stream) {#save_1}

Nesnenin verilerini belirtilen akışa kaydeder.

```csharp
public override void Save(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Nesnenin verilerinin kaydedileceği akış. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | Image seçenekleri olmadan Save yöntemini çağırmamalıyız. |

### Ayrıca bakınız

* class [Layer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* toplantı [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Dosya yolu. |
| options | ImageOptionsBase | Seçenekler. |

### Ayrıca bakınız

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* toplantı [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

Nesnenin verilerini belirtilen dosya konumuna kaydeder.

```csharp
public override void Save(string filePath, bool overWrite)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Nesnenin verilerinin kaydedileceği dosya yolu. |
| overWrite | Boolean | olarak ayarlanmışsa`doğru` üzerine dosya içeriğini yazın, aksi takdirde ekleme gerçekleşir. |

### Ayrıca bakınız

* class [Layer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* toplantı [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Görüntü verilerinin kaydedileceği akış. |
| optionsBase | ImageOptionsBase | Kaydetme seçenekleri. |
| boundsRectangle | Rectangle | Hedef görüntü dikdörtgeni sınırlar. Kaynak sınırlarını kullanmak için boş dikdörtgeni ayarlayın. |

### Ayrıca bakınız

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* toplantı [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Dosya yolu. |
| options | ImageOptionsBase | Seçenekler. |
| boundsRectangle | Rectangle | Hedef görüntü dikdörtgeni sınırlar. Kaynak sınırlarını kullanmak için boş dikdörtgeni ayarlayın. |

### Ayrıca bakınız

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* toplantı [Aspose.PSD](../../../)


