---
title: "ReadOnlyMode enum"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.ImageLoadOptions.ReadOnlyMode enum. PSD görüntüsü yüklenirken kullanılabilir yalnızca-okunur modları belirtir."
type: docs
weight: 5290
url: /tr/net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

Bir PSD görüntüsü yüklenirken kullanılabilir yalnızca okuma modlarını belirtir.

```csharp
public enum ReadOnlyMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | `0` | Hiçbir yalnızca-okunur kısıtlama uygulanmaz. Görüntü tamamen değiştirilebilir. |
| Default | `1` | Varsayılan mod. Görüntü tamamen yalnızca-okunur ve değiştirilemez. |
| MetadataEdit | `2` | Görüntü içeriği yalnızca-okunur iken görüntü meta verilerinin düzenlenmesine izin verir. |

## Örnekler

ReadOnlyMode.MetadataEdit kullanarak PSD meta verilerini düzenlemeyi ve kaydetmeyi gösterir.

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // ReadOnlyMode içinde meta verileri değiştir
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // ReadOnlyMode içinde değiştirilen meta verileri kaydet
    psdImage.Save(outputFile);
}

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(outputFile)) // Sets the of ReadOnlyMode to true
{
    AssertAreEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);
}

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects should be equal, but they don't.");
    }
}

void AssertAreNotEqual(object obj1, object obj2)
{
    if (object.Equals(obj1, obj2))
    {
        throw new Exception("Objects should not be equal, but they are equal.");
    }
}
```

### Ayrıca Bakınız

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


