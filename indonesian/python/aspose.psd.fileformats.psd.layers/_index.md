---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /id/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **Kelas** | **Deskripsi** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | Kelas lapisan artboard. |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | Rentang pencampuran. |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | Informasi saluran. |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | Bagian masker lapisan global. |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | Antarmuka dasar untuk pengaturan isi |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | Pemuat sumber daya lapisan. |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | Menjelaskan properti lapisan Shape. |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Lapisan psd. |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | Data rentang pencampuran lapisan. |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Kelas grup lapisan |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | Kalkulator Hash untuk Lapisan PSD. Ini dapat digunakan untuk menemukan lapisan yang sama atau berbeda dalam file PSD yang berbeda. |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | Mendefinisikan kelas dasar LayerMaskData yang berisi informasi tentang data masker lapisan dalam file PSD.<br/>            Ini dapat membantu memodifikasi file Adobe® Photoshop® secara programatik dan mengotomatiskan penyuntingan format PSD.<br/>            Jika lapisan hanya memiliki masker raster, ImageData berisi byte data masker raster.<br/>            Jika lapisan hanya memiliki masker vektor, ImageData berisi byte data masker vektor yang dirasterkan (cached).<br/>            Jika lapisan memiliki masker lapisan dan vektor, ImageData berisi masker raster dan masker vektor yang dirasterkan secara gabungan.<br/>            Panjang byte [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) harus sama dengan Lebar * Tinggi dari properti [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/).<br/>            Perhatikan, bahwa hanya menghapus / menambahkan / memperbarui LayerMaskData tidak cukup untuk penyimpanan yang benar<br/>            karena saluran tidak diperbarui; meskipun mungkin memberikan rendering yang tepat.<br/>            Metode [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) harus digunakan untuk itu. |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | Mendefinisikan kelas LayerMaskDataFull yang berisi informasi tentang data masker dalam lapisan file PSD<br/>            ketika lapisan memiliki masker lapisan dan vektor. Jika tidak, [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) digunakan.<br/>            ImageData berisi masker raster dan masker vektor yang dirasterkan secara gabungan.<br/>            Panjang byte ImageData harus sama dengan properti MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | Mendefinisikan kelas LayerMaskDataShort yang berisi informasi tentang data masker dalam lapisan file PSD<br/>            ketika lapisan hanya memiliki masker raster atau vektor tetapi tidak keduanya. Jika tidak, [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) digunakan.<br/>            Jika lapisan hanya memiliki masker raster, ImageData berisi byte data masker raster.<br/>            Jika lapisan hanya memiliki masker vektor, ImageData berisi byte data masker vektor yang dirasterkan (cached).<br/>            Panjang byte [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) harus sama dengan Lebar * Tinggi dari properti [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/). |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | Mewakili informasi lapisan. |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | Mendefinisikan registri sumber daya lapisan untuk memuat file PSD. |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | Kelas manajer lapisan tertaut. |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | Lapisan pembagi bagian untuk menandai batas folder (grup lapisan). |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Lapisan Shape. Mengenkapsulasi logika kerja dengan lapisan Shape dan sumber daya terkait. |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | Kelas lapisan teks. |
## **Enumerations**
| **Enumeration** | **Deskripsi** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | Bendera lapisan. |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | Bendera masker lapisan. |
