---
title: "Kelas LevlResource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource. Kelas LevlResource. Sumber daya dari Lapisan Penyesuaian Eksposur"
type: docs
weight: 2950
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
{{< psd/tize >}}
## LevlResource class

Kelas LevlResource. Sumber Daya Penyesuaian Paparan Layer.

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Menginisialisasi sebuah instance baru dari kelas `LevlResource`. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Menginisialisasi sebuah instance baru dari kelas `LevlResource`. Didukung dalam mode warna GrayScale, Duotone, RGB, CMYK, Lab 2 byte - Versi (=2) 29 * 10 byte - Set rekaman level dengan 5 bilangan bulat pendek 4 byte - Header Lvls (Mulai pada indeks 292) 2 byte - Versi (=3) 2 byte - Jumlah total rekaman level 10 * (Total Count - 29) Akhiran nol dari sumber daya Lvls juga harus dilipat menjadi empat. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Mendapatkan kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Mendapatkan tanda tangan. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Mendapatkan versi. Defaultnya adalah 2 |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Mendapatkan saluran. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan String yang mewakili instance ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | Kunci info alat tipe. |

### Lihat Juga

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


