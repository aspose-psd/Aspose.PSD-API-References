---
title: Class MixrResource
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource kelas. Kelas MixrResource. Sumber Daya Lapisan Penyesuaian Mixer Saluran
type: docs
weight: 2820
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
## MixrResource class

Kelas MixrResource. Sumber Daya Lapisan Penyesuaian Mixer Saluran

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Menginisialisasi instance baru dari`MixrResource` class. Spesifikasi format PSD berisi deskripsi berikut: 2 Versi ( = 1) 2 Monokrom 20 warna RGB atau CMYK plus konstanta untuk pengaturan mixer. 4 * 2 byte warna dengan 2 byte konstanta. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Menginisialisasi instance baru dari`MixrResource` class. Spesifikasi format PSD berisi deskripsi berikut: 2 Versi ( = 1) 2 Monokrom 20 warna RGB atau CMYK plus konstanta untuk pengaturan mixer. 4 * 2 byte warna dengan 2 byte konstanta. |

## Properti

| Nama | Keterangan |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/key/) { get; } | Mendapat kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah ini`MixrResource` adalah monokrom. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/psdversion/) { get; } | Mendapatkan versi psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Mendapat tanda tangan. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Mendapatkan atau menyetel versi. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Mendapatkan data mentah informasi saluran |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke wadah aliran yang ditentukan. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Mengatur informasi saluran. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | Kunci info alat ketik. |

### Lihat juga

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* perakitan [Aspose.PSD](../../)


