---
title: Class LinkResource
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource kelas. Menentukan kelas LinkResource yang berisi informasi tentang file yang ditautkan atau disematkan dalam gambar format PSD. Sumber tautan mungkin berisi beberapaLinkDataSource instance yang dapat diakses oleh pengindeks di kelas turunan mana pun.
type: docs
weight: 2710
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
## LinkResource class

Menentukan kelas LinkResource yang berisi informasi tentang file yang ditautkan atau disematkan dalam gambar format PSD. Sumber tautan mungkin berisi beberapa[`LinkDataSource`](../linkdatasource/) instance yang dapat diakses oleh pengindeks di kelas turunan mana pun.

```csharp
public abstract class LinkResource : LayerResource
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Mendapat jumlah sumber data tautan yang dapat diakses oleh pengindeks. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Mendapat nilai yang menunjukkan apakah instance sumber daya tautan ini kosong. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Mendapatkan[`LinkDataSource`](../linkdatasource/) pada indeks yang ditentukan yang merupakan pengidentifikasi unik sumber data tautan.. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Mendapat kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Mendapatkan panjang sumber daya tautan global PSD dalam satuan byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | Mendapatkan versi format PSD. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | Mendapatkan tanda tangan sumber daya tautan global PSD. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Menyimpan data blok sumber daya. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

### Lihat juga

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* perakitan [Aspose.PSD](../../)


