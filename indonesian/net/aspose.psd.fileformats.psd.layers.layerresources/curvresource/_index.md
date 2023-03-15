---
title: Class CurvResource
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource kelas. Kelas CurvResource. Resource of Curves Adjustment Layer 1 byte  0 jika menggunakan kurva 1 jika menggunakan piksel pada map jika 0 maka 2 byte  pendek. Standarnya adalah 1 4 byte  int. Digunakan hanya byte terakhir demi sedikit. Bit pertama untuk 1 saluran Bit keempat untuk 4 saluran misalnya 2 byte  titik pendek count 4 byte  jumlah titik  titik kurva 2 pendek posisi pertama tinggi kedua 4 byte  kata Crv 2 byte  pendek default adalah 4 untuk Curves 4 byte  int. Standarnya adalah 1 4 byte  point count 4 byte  point count  point of curve 2 short posisi pertama tinggi kedua 04 byte  Leading to fold for four if 1 then 2 bytes  short. Standarnya adalah 1 4 byte  int. Digunakan hanya byte terakhir. Satu saluran dalam satu bit. Bit pertama untuk 1 saluran Bit keempat untuk 4 saluran misalnya 256  jumlah saluran yang diubah  nilai urutan saluran dalam rentang 0  255 4 byte  kata Crv  2 byte  pendek. Standarnya adalah 3 untuk piksel pada map 4 byte  int Jumlah saluran 2  256 byte  pendek 2 untuk indeks saluran 256 adalah nilai urutan saluran dalam rentang 0  255
type: docs
weight: 2400
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
## CurvResource class

Kelas CurvResource. Resource of Curves Adjustment Layer 1 byte - 0 jika menggunakan kurva, 1 jika menggunakan piksel pada map jika 0 maka: 2 byte - pendek. Standarnya adalah 1 4 byte - int. Digunakan hanya byte terakhir demi sedikit. Bit pertama untuk 1 saluran, Bit keempat untuk 4 saluran misalnya 2 byte - titik pendek count 4 byte * jumlah titik - titik kurva 2 pendek: posisi pertama, tinggi kedua 4 byte - kata "Crv" 2 byte - pendek default adalah 4 untuk Curves 4 byte - int. Standarnya adalah 1 4 byte - point count 4 byte * point count - point of curve 2 short: posisi pertama, tinggi kedua 0-4 byte - Leading to fold for four if 1 then: 2 bytes - short. Standarnya adalah 1 4 byte - int. Digunakan hanya byte terakhir. Satu saluran dalam satu bit. Bit pertama untuk 1 saluran, Bit keempat untuk 4 saluran misalnya 256 * jumlah saluran yang diubah - nilai urutan saluran dalam rentang 0 - 255 4 byte - kata "Crv " 2 byte - pendek. Standarnya adalah 3 untuk piksel pada map 4 byte - int Jumlah saluran (2 + 256) byte - pendek 2 untuk indeks saluran, 256 adalah nilai urutan saluran dalam rentang 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Menginisialisasi instance baru dari`CurvResource` kelas. |
| [CurvResource](curvresource/#constructor_1)(int) | Menginisialisasi instance baru dari`CurvResource` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini adalah data yang disimpan secara terpisah. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/key/) { get; } | Mendapat kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/psdversion/) { get; } | Mendapatkan versi psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Mendapat tanda tangan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Mendapat manajer aktif. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Mendapatkan data saluran. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Mendapatkan manajer kurva. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke wadah aliran yang ditentukan. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | Kunci info alat ketik. |

### Lihat juga

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* perakitan [Aspose.PSD](../../)


