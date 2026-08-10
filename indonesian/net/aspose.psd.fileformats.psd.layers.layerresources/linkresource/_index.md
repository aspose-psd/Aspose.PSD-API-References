---
title: "Kelas LinkResource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource. Mendefinisikan kelas LinkResource yang berisi informasi tentang file yang ditautkan atau disematkan dalam gambar format PSD. Sumber daya tautan dapat berisi beberapa instance LinkDataSource yang dapat diakses melalui pengindeks dalam kelas turunan mana pun"
type: docs
weight: 3010
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
{{< psd/tize >}}
## LinkResource class

Mendefinisikan kelas LinkResource yang berisi informasi tentang file yang ditautkan atau disematkan dalam gambar format PSD. Sumber daya tautan dapat berisi beberapa instance [`LinkDataSource`](../linkdatasource/) yang dapat diakses melalui pengindeks dalam kelas turunan mana pun.

```csharp
public abstract class LinkResource : LayerResource
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Mendapatkan jumlah sumber data tautan yang dapat diakses melalui indeks. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Mendapatkan nilai yang menunjukkan apakah instance sumber daya tautan ini kosong. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Mendapatkan [`LinkDataSource`](../linkdatasource/) pada indeks yang ditentukan yang merupakan pengidentifikasi unik sumber data tautan. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Mendapatkan kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Mendapatkan panjang sumber daya tautan global PSD dalam byte. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Mendapatkan tanda tangan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Menyimpan data blok sumber daya. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan String yang mewakili instance ini. |

### Lihat Juga

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


