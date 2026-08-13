---
title: "Layer.Save"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Katman yöntemi. Nesnenin verilerini belirtilen akışa kaydeder"
type: docs
weight: 390
url: /tr/net/aspose.psd.fileformats.psd.layers/layer/save/
---
{{< psd/tize >}}
## Save(Stream) {#save_1}

Nesnenin verilerini belirtilen akışa kaydeder.

```csharp
public override void Save(Stream stream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Nesnenin verilerini kaydetmek için akış. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | Görüntü seçenekleri olmadan Save yöntemini çağırmamalıyız |

### Ayrıca Bakınız

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Dosya yolu. |
| seçenekler | ImageOptionsBase | Seçenekler. |

### Ayrıca Bakınız

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

Nesnenin verilerini belirtilen dosya konumuna kaydeder.

```csharp
public override void Save(string filePath, bool overWrite)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Nesnenin verilerini kaydetmek için dosya yolu. |
| overWrite | Boolean | `true` olarak ayarlanırsa dosya içeriği üzerine yazar, aksi takdirde ekleme yapılır. |

### Ayrıca Bakınız

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Görüntünün verilerini kaydetmek için akış. |
| optionsBase | ImageOptionsBase | Kaydetme seçenekleri. |
| boundsRectangle | Rectangle | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırlarını kullanmak için boş dikdörtgeni ayarlayın. |

### Ayrıca Bakınız

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Dosya yolu. |
| seçenekler | ImageOptionsBase | Seçenekler. |
| boundsRectangle | Rectangle | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırlarını kullanmak için boş dikdörtgeni ayarlayın. |

### Ayrıca Bakınız

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


