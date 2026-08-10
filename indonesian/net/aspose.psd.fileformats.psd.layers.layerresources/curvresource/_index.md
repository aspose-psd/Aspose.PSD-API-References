---
title: "Kelas CurvResource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource. Kelas CurvResource. Sumber daya dari Lapisan Penyesuaian Kurva 1 byte  0 jika menggunakan kurva 1 jika menggunakan piksel pada peta jika 0 maka 2 byte  short. Nilai default adalah 1 4 byte  int. Hanya byte terakhir yang digunakan per bit. Bit pertama untuk 1 saluran, bit keempat untuk 4 saluran, misalnya 2 byte  short jumlah titik 4 byte  jumlah titik  titik kurva 2 short posisi pertama tinggi kedua 4 byte  word Crv  2 byte  short default adalah 4 untuk Kurva 4 byte  int. Nilai default adalah 1 4 byte  jumlah titik 4 byte  jumlah titik  titik kurva 2 short posisi pertama tinggi kedua 04 byte  Menjadi lipatan untuk empat jika 1 maka 2 byte  short. Nilai default adalah 1 4 byte  int. Hanya byte terakhir yang digunakan. Satu saluran berada dalam satu bit. Bit pertama untuk 1 saluran, bit keempat untuk 4 saluran, misalnya 256  jumlah saluran yang berubah  nilai terurut saluran dalam rentang 0‑255 4 byte  word Crv  2 byte  short. Nilai default adalah 3 untuk piksel pada peta 4 byte  int Jumlah saluran 2  256 byte  short 2 untuk indeks saluran 256 adalah nilai terurut saluran dalam rentang 0‑255"
type: docs
weight: 2660
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
{{< psd/tize >}}
## CurvResource class

Kelas CurvResource. Sumber daya dari Lapisan Penyesuaian Kurva 1 byte - 0 jika menggunakan kurva, 1 jika menggunakan peta piksel; jika 0 maka: 2 byte - short. Defaultnya 1 4 byte - int. Hanya byte terakhir yang digunakan per bit. Bit pertama untuk 1 kanal, bit keempat untuk 4 kanal, misalnya 2 byte - short jumlah titik 4 byte * jumlah titik - titik-titik kurva 2 short: posisi pertama, tinggi kedua 4 byte - kata \"Crv \" 2 byte - short defaultnya 4 untuk Kurva 4 byte - int. Defaultnya 1 4 byte - jumlah titik 4 byte * jumlah titik - titik-titik kurva 2 short: posisi pertama, tinggi kedua 0-4 byte - Leading to be fold for four if 1 then: 2 byte - short. Defaultnya 1 4 byte - int. Hanya byte terakhir yang digunakan. Satu kanal berada dalam satu bit. Bit pertama untuk 1 kanal, bit keempat untuk 4 kanal, misalnya 256 * jumlah kanal yang diubah - nilai terurut kanal dalam rentang 0 - 255 4 byte - kata \"Crv \" 2 byte - short. Defaultnya 3 untuk peta piksel 4 byte - int Jumlah kanal (2 + 256) byte - short 2 untuk indeks kanal, 256 adalah nilai terurut kanal dalam rentang 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Menginisialisasi sebuah instance baru dari kelas `CurvResource`. |
| [CurvResource](curvresource/#constructor_1)(int) | Menginisialisasi sebuah instance baru dari kelas `CurvResource`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini menyimpan data secara terpisah. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Mendapatkan kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Mendapatkan tanda tangan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Mendapatkan manajer aktif. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Mendapatkan data saluran. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Mendapatkan manajer kurva. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan String yang mewakili instance ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | Kunci info alat tipe. |

### Lihat Juga

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


