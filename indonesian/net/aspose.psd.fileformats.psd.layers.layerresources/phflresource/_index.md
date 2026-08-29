---
title: "Kelas PhflResource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource. Kelas PhflResource. Sumber daya dari Exposure Adjustment Layer 2 Versi 3 atau 2, 12 4 byte masing‑masing untuk warna XYZ. Hanya di Versi 3: 10 2 byte ruang warna diikuti oleh 4 2 byte komponen warna. Hanya di Versi 2: 4 Density 1 Preserve Luminosity"
type: docs
weight: 3240
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
{{< psd/tize >}}
## PhflResource class

Kelas PhflResource. Sumber daya Lapisan Penyesuaian Exposure 2 Versi (= 3) atau (= 2) 12 4 byte masing-masing untuk warna XYZ (Hanya pada Versi 3) 10 2 byte ruang warna diikuti oleh 4 * 2 byte komponen warna (Hanya pada Versi 2) 4 Kepadatan 1 Pertahankan Luminositas

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Mendapatkan atau mengatur kepadatan. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Mendapatkan kunci sumber daya lapisan. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Mendapatkan tanda tangan. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Mendapatkan versi. Defaultnya adalah 2 atau 3. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | Mendapatkan warna RGB. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | Mengatur warna RGB. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan String yang mewakili instance ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | Kunci info alat tipe. |

### Lihat Juga

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


