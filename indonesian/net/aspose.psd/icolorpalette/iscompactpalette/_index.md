---
title: "IColorPalette.IsCompactPalette"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti IColorPalette. Mendapatkan nilai yang menunjukkan apakah palet kompak digunakan"
type: docs
weight: 40
url: /id/net/aspose.psd/icolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## IColorPalette.IsCompactPalette property

Mendapatkan nilai yang menunjukkan apakah palet kompak digunakan.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` jika palet kompak digunakan; jika tidak, `false`.

## Catatan

Palet kompak berarti gambar hanya akan berisi entri palet yang ditentukan bila memungkinkan, atau dengan kata lain gambar akan lebih kompak dan memakan ruang lebih sedikit; jika tidak, akan ada 2^BitsPerPixel entri dan gambar akan menyisakan lebih banyak ruang untuk semua kemungkinan entri palet. Menetapkan nilai ini ke true dan mengubah entri palet dapat menyebabkan penalti kinerja karena pergerakan data dapat terjadi, jadi gunakan dengan hati-hati.

### Lihat Juga

* interface [IColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


