---
title: "Kelas MixrResource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource. Kelas MixrResource. Sumber daya dari Lapisan Penyesuaian Mixer Saluran"
type: docs
weight: 3160
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
{{< psd/tize >}}
## MixrResource class

Kelas MixrResource. Sumber daya Lapisan Penyesuaian Channel Mixer

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Menginisialisasi sebuah instance baru dari kelas `MixrResource`. Spesifikasi format PSD berisi deskripsi berikut: 2 Versi (= 1) 2 Monokrom 20 warna RGB atau CMYK ditambah konstanta untuk pengaturan mixer. 4 * 2 byte warna dengan 2 byte konstanta. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Menginisialisasi sebuah instance baru dari kelas `MixrResource`. Spesifikasi format PSD berisi deskripsi berikut: 2 Versi (= 1) 2 Monokrom 20 warna RGB atau CMYK ditambah konstanta untuk pengaturan mixer. 4 * 2 byte warna dengan 2 byte konstanta. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Mendapatkan kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah `MixrResource` ini monokrom. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Mendapatkan tanda tangan. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Mendapatkan atau mengatur versi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Mendapatkan data mentah informasi saluran |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Mengatur informasi saluran. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan String yang mewakili instance ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | Kunci info alat tipe. |

### Lihat Juga

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


