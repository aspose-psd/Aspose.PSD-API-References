---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: Aspose.PSD untuk Referensi .NET API
description: Ruang nama berisi lapisan format file PSD.
type: docs
weight: 210
url: /id/net/aspose.psd.fileformats.psd.layers/
---
Ruang nama berisi lapisan format file PSD.

## Kelas

| Kelas | Keterangan |
| --- | --- |
| [BlendRange](./blendrange/) | Rentang campuran. |
| [ChannelInformation](./channelinformation/) | Informasi saluran. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | Bagian layer mask global. |
| [Layer](./layer/) | Lapisan psd. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Data rentang pencampuran layer. |
| [LayerGroup](./layergroup/) | Kelas lapisan grup |
| [LayerHashCalculator](./layerhashcalculator/) | Kalkulator Hash untuk Lapisan PSD. Ini dapat digunakan untuk menemukan lapisan yang sama atau berbeda dalam file PSD yang berbeda |
| [LayerMaskData](./layermaskdata/) | Menentukan kelas LayerMaskData dasar yang berisi informasi tentang data layer mask dalam file PSD. Ini dapat membantu memodifikasi file Adobe® Photoshop® secara terprogram dan mengotomatiskan pengeditan format PSD. Jika layer hanya memiliki masker raster, ImageData berisi raster mask data bytes. Jika layer hanya memiliki mask vektor, ImageData berisi byte data raster (cache) mask vektor. Jika layer memiliki layer dan mask vektor, ImageData berisi masker raster dan masker vektor raster digabungkan. Itu[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)panjang byte harus sama dengan Lebar * Tinggi[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) properties. Perhatikan, bahwa menghapus / menambah / memperbarui LayerMaskData saja tidak cukup untuk menyimpan dengan benar karena saluran tidak diperbarui; meskipun mungkin memberikan rendering yang benar. The[`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) metode harus digunakan untuk itu. |
| [LayerMaskDataFull](./layermaskdatafull/) | Mendefinisikan kelas LayerMaskDataFull yang berisi informasi tentang data mask di file PSD layer saat layer memiliki layer dan mask vektor. Jika tidak, a[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) digunakan. ImageData berisi topeng raster dan gabungan topeng vektor raster. Panjang byte ImageData harus sama dengan properti MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](./layermaskdatashort/) | Mendefinisikan kelas LayerMaskDataShort yang berisi informasi tentang data mask di file PSD layer ketika layer hanya memiliki mask raster atau vektor tetapi tidak keduanya. Jika tidak, a[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) digunakan. Jika layer hanya memiliki topeng raster, ImageData berisi byte data topeng raster. Jika lapisan hanya memiliki topeng vektor, ImageData berisi byte data raster (cache) topeng vektor. [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)panjang byte harus sama dengan Lebar * Tinggi[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) properti. |
| [LayerResource](./layerresource/) | Merupakan info lapisan. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Menentukan registri sumber daya lapisan untuk pemuatan file PSD. |
| [LinkedLayersManager](./linkedlayersmanager/) | Kelas manajer lapisan tertaut. |
| [SectionDividerLayer](./sectiondividerlayer/) | Layer pembagi bagian untuk menandai batas folder (grup layer). |
| [TextLayer](./textlayer/) | Kelas lapisan teks |
## Antarmuka

| Antarmuka | Keterangan |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Antarmuka dasar untuk pengaturan isian |
| [ILayerResourceLoader](./ilayerresourceloader/) | Pemuat sumber daya lapisan. |
## Pencacahan

| Pencacahan | Keterangan |
| --- | --- |
| [LayerFlags](./layerflags/) | Bendera lapisan |
| [LayerMaskFlags](./layermaskflags/) | Bendera layer mask |


