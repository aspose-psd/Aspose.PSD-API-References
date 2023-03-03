---
title: Class ImageLoadersRegistry
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.ImageLoadersRegistry kelas. Mewakili registri pemuat gambar.
type: docs
weight: 4780
url: /id/net/aspose.psd/imageloadersregistry/
---
## ImageLoadersRegistry class

Mewakili registri pemuat gambar.

```csharp
public static class ImageLoadersRegistry
```

## Properti

| Nama | Keterangan |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Mendapat deskriptor terdaftar. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Mendapat format pemuatan gambar terdaftar. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Membuat loader pertama yang ditemukan cocok untuk yang ditentukan*stream* dan opsional*loadOptions* . |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Mendapat peninju yang ditemukan deskriptor yang didukung cocok untuk yang ditentukan*stream* dan opsional*loadOptions* . |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Mendapatkan format file pertama yang didukung dengan nama jenisnya. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Mendapatkan deskriptor pertama yang didukung dengan nama jenisnya. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Mendaftarkan deskripsi pemuat gambar yang ditentukan. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Mendaftarkan loader. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Membatalkan pendaftaran loader. |

### Lihat juga

* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)


