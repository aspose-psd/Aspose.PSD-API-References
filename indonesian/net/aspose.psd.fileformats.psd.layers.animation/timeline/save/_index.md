---
title: "Timeline.Save"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode Timeline. Menyimpan PsdImages dan data Timeline ke lokasi file yang ditentukan dalam format yang ditentukan sesuai opsi penyimpanan"
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

Menyimpan data PsdImage dan Timeline ke lokasi file yang ditentukan dalam format yang ditentukan sesuai opsi penyimpanan.

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file. |
| opsi | ImageOptionsBase | Opsi. |

## Contoh

Kode berikut menunjukkan dukungan ekspor Timeline ke gambar Gif.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Lihat Juga

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

Menyimpan data PsdImage dan Timeline ke aliran yang ditentukan dalam format yang ditentukan sesuai opsi penyimpanan.

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Aliran output. |
| opsi | ImageOptionsBase | Opsi. |

## Contoh

Kode berikut menunjukkan dukungan ekspor Timeline ke gambar Gif.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Lihat Juga

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


