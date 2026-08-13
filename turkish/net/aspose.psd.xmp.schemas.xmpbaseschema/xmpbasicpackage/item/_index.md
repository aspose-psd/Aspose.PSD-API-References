---
title: "XmpBasicPackage.Item"
second_title: "Aspose.PSD for .NET API Referansı"
description: "XmpBasicPackage özelliği. Belirtilen anahtara sahip Object'i alır veya ayarlar"
type: docs
weight: 20
url: /tr/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

Belirtilen anahtara sahip Nesneyi alır veya ayarlar.

```csharp
public override object this[string key] { get; set; }
```

| Parametre | Açıklama |
| --- | --- |
| anahtar | Değeri tanımlayan anahtar. |

### Dönüş Değeri

Belirtilen anahtara sahip Object'i döndürür.

### Property Value

Object.

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

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


