---
title: "Kelas BritResource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource. Kelas BritResource. Sumber daya dari Lapisan Penyesuaian Kecerahan/Kontras"
type: docs
weight: 2600
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
{{< psd/tize >}}
## BritResource class

Kelas BritResource. Sumber daya dari Lapisan Penyesuaian Kecerahan/Kontras

```csharp
public class BritResource : AdjustmentLayerResource
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [BritResource](britresource/#constructor)() | Menginisialisasi sebuah instance baru dari kelas `BritResource`. |
| [BritResource](britresource/#constructor_1)(byte[]) | Menginisialisasi sebuah instance baru dari kelas `BritResource`. Spesifikasi format PSD berisi deskripsi berikut: 2 Kecerahan 2 Kontras 2 Nilai rata‑rata untuk kecerahan dan kontras 1 Hanya warna Lab. Tidak digunakan dalam PSD modern (CS5 ke atas) dimana CgEd berada. CgEd menyimpan properti informasi. |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | Menginisialisasi sebuah instance baru dari kelas `BritResource`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | Mendapatkan atau mengatur kecerahan. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | Mendapatkan atau mengatur kontras. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Mendapatkan kunci sumber daya lapisan. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [lab color]. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | Mendapatkan atau mengatur nilai rata-rata untuk kecerahan dan kontras. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Mendapatkan tanda tangan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan String yang mewakili instance ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | Kunci info alat tipe. |

### Lihat Juga

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


