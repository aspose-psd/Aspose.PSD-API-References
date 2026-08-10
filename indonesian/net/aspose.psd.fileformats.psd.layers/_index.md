---
title: "Aspose.PSD.FileFormats.Psd.Layers"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Namespace ini berisi lapisan format file PSD"
type: docs
weight: 230
url: /id/net/aspose.psd.fileformats.psd.layers/
---
{{< psd/tize >}}
Namespace ini berisi lapisan format file PSD.

## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [ArtboardLayer](./artboardlayer/) | Kelas lapisan artboard. |
| [BlendRange](./blendrange/) | Rentang blend. |
| [ChannelInformation](./channelinformation/) | Informasi saluran. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | Bagian topeng lapisan global. |
| [Layer](./layer/) | Lapisan psd. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Data rentang pencampuran lapisan. |
| [LayerGroup](./layergroup/) | Kelas lapisan grup |
| [LayerHashCalculator](./layerhashcalculator/) | Kalkulator Hash untuk Lapisan PSD. Ini dapat digunakan untuk menemukan lapisan yang sama atau berbeda dalam file PSD yang berbeda. |
| [LayerMaskData](./layermaskdata/) | Menetapkan kelas dasar LayerMaskData yang berisi informasi tentang data topeng lapisan dalam file PSD. Ini dapat membantu memodifikasi file Adobe® Photoshop® secara programatis dan mengotomatiskan penyuntingan format PSD. Jika lapisan hanya memiliki topeng raster, ImageData berisi byte data topeng raster. Jika lapisan hanya memiliki topeng vektor, ImageData berisi byte data topeng vektor yang dirasterisasi (cached). Jika lapisan memiliki kedua topeng lapisan dan vektor, ImageData berisi gabungan topeng raster dan topeng vektor yang dirasterisasi. Panjang byte [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) harus sama dengan Lebar * Tinggi dari properti [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/). Perhatikan bahwa hanya menghapus / menambahkan / memperbarui LayerMaskData tidak cukup untuk penyimpanan yang benar karena saluran tidak diperbarui; meskipun dapat memberikan rendering yang tepat. Metode [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) harus digunakan untuk itu. |
| [LayerMaskDataFull](./layermaskdatafull/) | Menetapkan kelas LayerMaskDataFull yang berisi informasi tentang data topeng dalam lapisan file PSD ketika lapisan memiliki kedua topeng lapisan dan vektor. Jika tidak, digunakan [`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/). ImageData berisi gabungan topeng raster dan topeng vektor yang dirasterisasi. Panjang byte ImageData harus sama dengan properti MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](./layermaskdatashort/) | Menetapkan kelas LayerMaskDataShort yang berisi informasi tentang data topeng dalam lapisan file PSD ketika lapisan hanya memiliki topeng raster atau vektor tetapi tidak keduanya. Jika tidak, digunakan [`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/). Jika lapisan hanya memiliki topeng raster, ImageData berisi byte data topeng raster. Jika lapisan hanya memiliki topeng vektor, ImageData berisi byte data topeng vektor yang dirasterisasi (cached). Panjang byte [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) harus sama dengan Lebar * Tinggi dari properti [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/). |
| [LayerResource](./layerresource/) | Mewakili informasi lapisan. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Mendefinisikan registri sumber daya lapisan untuk pemuatan file PSD. |
| [LinkedLayersManager](./linkedlayersmanager/) | Kelas manajer lapisan terkait. |
| [SectionDividerLayer](./sectiondividerlayer/) | Lapisan pembagi bagian untuk menandai batas folder (grup lapisan). |
| [ShapeLayer](./shapelayer/) | Lapisan Bentuk. Membungkus logika kerja dengan lapisan Bentuk dan sumber daya terkait. |
| [TextLayer](./textlayer/) | Kelas lapisan teks |
## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Antarmuka dasar untuk pengaturan isi |
| [ILayerResourceLoader](./ilayerresourceloader/) | Pemuat sumber daya lapisan. |
| [IShapeLayer](./ishapelayer/) | Menjelaskan properti lapisan Bentuk. |
## Enumerasi

| Enumerasi | Deskripsi |
| --- | --- |
| [LayerFlags](./layerflags/) | Bendera lapisan |
| [LayerMaskFlags](./layermaskflags/) | Bendera topeng lapisan |


