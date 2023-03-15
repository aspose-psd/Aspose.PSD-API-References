---
title: Class PhflResource
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource kelas. Kelas PhflResource. Resource of Exposure Adjustment Layer 2 Versi   3  atau   2  masingmasing 12 4 byte untuk warna XYZHanya di Versi 3 10 2 byte ruang warna diikuti oleh 4  2 byte komponen warnaHanya di Versi 2 4 Kepadatan 1 Pertahankan Kecerahan
type: docs
weight: 2890
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
## PhflResource class

Kelas PhflResource. Resource of Exposure Adjustment Layer 2 Versi ( = 3 ) atau ( = 2 ) masing-masing 12 4 byte untuk warna XYZ(Hanya di Versi 3) 10 2 byte ruang warna diikuti oleh 4 * 2 byte komponen warna(Hanya di Versi 2) 4 Kepadatan 1 Pertahankan Kecerahan

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Mendapat atau menyetel kepadatan. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/key/) { get; } | Mendapat kunci sumber daya lapisan. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [mempertahankan luminositas]. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/psdversion/) { get; } | Mendapatkan versi psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Mendapat tanda tangan. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Mendapatkan versinya. Standarnya adalah 2 atau 3 |

## Metode

| Nama | Keterangan |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | Mendapatkan warna RGB. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke wadah aliran yang ditentukan. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | Mengatur warna RGB. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | Kunci info alat ketik. |

### Lihat juga

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* perakitan [Aspose.PSD](../../)


