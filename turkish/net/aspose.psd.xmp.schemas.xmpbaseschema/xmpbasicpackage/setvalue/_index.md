---
title: "XmpBasicPackage.SetValue"
second_title: "Aspose.PSD for .NET API Referansı"
description: "XmpBasicPackage yöntemi. Değeri ayarlar"
type: docs
weight: 120
url: /tr/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

Değeri ayarlar.

```csharp
public override void SetValue(string key, IXmlValue value)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | String | Eklenen değerle tanımlanan anahtarın dize temsili. |
| değer | IXmlValue | Eklenecek değer. |

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

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


