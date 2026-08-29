---
title: "PsdColorPalette.IsCompactPalette"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti PsdColorPalette. Mendapatkan nilai yang menunjukkan apakah palet tersebut kompak"
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## PsdColorPalette.IsCompactPalette property

Mengambil nilai yang menunjukkan apakah paletnya kompak.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` jika palet tersebut kompak; jika tidak, `false`.

## Catatan

Palet kompak berarti gambar hanya akan berisi entri palet yang ditentukan bila memungkinkan, atau dengan kata lain gambar akan lebih kompak dan memakan ruang lebih sedikit; jika tidak, akan ada 2^BitsPerPixel entri dan gambar akan menyisakan lebih banyak ruang untuk semua kemungkinan entri palet. Menetapkan nilai ini ke true dan mengubah entri palet dapat menyebabkan penalti kinerja karena pergerakan data dapat terjadi, jadi gunakan dengan hati-hati.

### Lihat Juga

* class [PsdColorPalette](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


