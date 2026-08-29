---
title: "Kelas PhflResourceVersion2"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion2. Kelas PhflResource. Sumber daya dari Layer Penyesuaian Eksposur 2 Versi 3 atau 2. 12 4 byte masing-masing untuk warna XYZ hanya pada Versi 3, 10 2 byte ruang warna diikuti oleh 4 2 byte komponen warna hanya pada Versi 2, 4 Kepadatan 1, Mempertahankan Luminositas."
type: docs
weight: 3250
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---
{{< psd/tize >}}
## PhflResourceVersion2 class

Kelas PhflResource. Sumber daya Lapisan Penyesuaian Exposure 2 Versi (= 3) atau (= 2) 12 4 byte masing-masing untuk warna XYZ (Hanya pada Versi 3) 10 2 byte ruang warna diikuti oleh 4 * 2 byte komponen warna (Hanya pada Versi 2) 4 Kepadatan 1 Pertahankan Luminositas

```csharp
public class PhflResourceVersion2 : PhflResource
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PhflResourceVersion2](phflresourceversion2/#constructor)() | Menginisialisasi instance baru dari kelas `PhflResourceVersion2`. |
| [PhflResourceVersion2](phflresourceversion2/#constructor_1)(byte[]) | Menginisialisasi instance baru dari kelas `PhflResourceVersion2`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/colorspace/) { get; } | Mendapatkan ruang warna. |
| [ComponentA](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componenta/) { get; set; } | Mendapatkan atau mengatur komponen A dari warna |
| [ComponentB](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentb/) { get; set; } | Mendapatkan atau mengatur komponen B |
| [ComponentL](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentl/) { get; set; } | Mendapatkan atau mengatur komponen L dari warna |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Mendapatkan atau mengatur kepadatan. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Mendapatkan kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Mendapatkan tanda tangan. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/version/) { get; } | Mendapatkan versi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/getrgbcolor/)() | Mendapatkan warna. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/save/)(StreamContainer, int) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/setrgbcolor/)(Color) | Mengatur warna RGB. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan String yang mewakili instance ini. |

### Lihat Juga

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


