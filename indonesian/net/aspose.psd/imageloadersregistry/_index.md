---
title: "Kelas ImageLoadersRegistry"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.ImageLoadersRegistry. Mewakili registri pemuat gambar"
type: docs
weight: 5270
url: /id/net/aspose.psd/imageloadersregistry/
---
{{< psd/tize >}}
## ImageLoadersRegistry class

Mewakili registri pemuat gambar.

```csharp
public static class ImageLoadersRegistry
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Mendapatkan deskriptor yang terdaftar. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Mendapatkan format pemuatan gambar yang terdaftar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Membuat pemuat pertama yang ditemukan yang cocok untuk *stream* yang ditentukan dan opsional *loadOptions*. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Mendapatkan deskriptor yang didukung pertama yang ditemukan yang cocok untuk *stream* yang ditentukan dan opsional *loadOptions*. |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Mendapatkan format file yang didukung pertama berdasarkan nama tipenya. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Mendapatkan deskriptor pertama yang didukung berdasarkan nama tipenya. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Mendaftarkan deskriptor pemuat gambar yang ditentukan. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Mendaftarkan pemuat. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Membatalkan pendaftaran pemuat. |

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


