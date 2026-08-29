---
title: "Kelas LayerResourcesRegistry"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry kelas. Menentukan registri sumber daya lapisan untuk pemuatan file PSD"
type: docs
weight: 3790
url: /id/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
{{< psd/tize >}}
## LayerResourcesRegistry class

Mendefinisikan registri sumber daya lapisan untuk pemuatan file PSD.

```csharp
public static class LayerResourcesRegistry
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | Mendapatkan deskriptor yang terdaftar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | Mendapatkan deskriptor pembuka pertama yang didukung. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | Mendapatkan deskriptor pertama yang didukung berdasarkan nama tipenya. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | Memuat [`LayerResource`](../layerresource/) menggunakan pembuka pertama yang ditemukan yang cocok untuk *stream* yang ditentukan. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | Mendaftarkan pembuka. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | Membatalkan pendaftaran pembuka. |

### Lihat Juga

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


