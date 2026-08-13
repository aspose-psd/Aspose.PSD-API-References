---
title: "Timeline.Save"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Timeline yöntemi. PsdImages ve Timeline verilerini, kaydetme seçeneklerine göre belirtilen dosya konumuna belirtilen formatta kaydeder."
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

PsdImage ve Timeline verilerini, kaydetme seçeneklerine göre belirtilen formatta belirtilen dosya konumuna kaydeder.

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Dosya yolu. |
| seçenekler | ImageOptionsBase | Seçenekler. |

## Örnekler

Aşağıdaki kod, Timeline'ın Gif görüntüsüne dışa aktarım desteğini gösterir.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Ayrıca Bakınız

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

PsdImage ve Timeline verilerini, kaydetme seçeneklerine göre belirtilen formatta belirtilen akışa kaydeder.

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Çıktı akışı. |
| seçenekler | ImageOptionsBase | Seçenekler. |

## Örnekler

Aşağıdaki kod, Timeline'ın Gif görüntüsüne dışa aktarım desteğini gösterir.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Ayrıca Bakınız

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


