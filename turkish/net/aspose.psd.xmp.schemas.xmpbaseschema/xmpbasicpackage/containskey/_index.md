---
title: "XmpBasicPackage.ContainsKey"
second_title: "Aspose.PSD for .NET API Referansı"
description: "XmpBasicPackage yöntemi. Belirtilen anahtarın anahtar içerip içermediğini belirler"
type: docs
weight: 40
url: /tr/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/containskey/
---
{{< psd/tize >}}
## XmpBasicPackage.ContainsKey method

Belirtilen anahtarın anahtar içerip içermediğini belirler.

```csharp
public override bool ContainsKey(string key)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | String | Kontrol edilecek anahtar. |

### Dönüş Değeri

Belirtilen anahtar anahtar içeriyorsa true döndürür.

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


