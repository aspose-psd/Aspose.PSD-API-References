---
title: "PsdOptions.UpdateMetadata"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdOptions özelliği. Meta verilerin güncellenip güncellenmeyeceğini belirten bir değeri alır veya ayarlar. Değer true ise, bir görüntü kaydedilirken meta veriler güncellenecektir."
type: docs
weight: 110
url: /tr/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

Metadataları [update metadata] güncelleme seçeneğini gösteren bir değeri alır veya ayarlar. Değer true ise, görüntü kaydedilirken metadata güncellenir.

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` eğer [update metadata] ise; aksi takdirde `false`.

## Örnekler

Aşağıdaki kod, xmp verilerinde CreatorTool değerini güncellemek için UpdateMetadata seçeneğinin kullanımını gösterir.

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // Creator tool'un değişmesini istiyorsanız, \"UpdateMetadata\" özelliğinin true olarak ayarlandığından emin olun. Varsayılan olarak true ayarlanmıştır.
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // Görüntü kaydediliyor. 
    image.Save(path, psdOptions);

    // Kod içinde creator tool kontrol ediliyor.
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // Burada creator tool bilgisi güncellenecek.
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### Ayrıca Bakınız

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


