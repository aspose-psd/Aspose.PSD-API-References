---
title: "PsdLoadOptions.ReadOnlyType"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdLoadOptions özelliği. PSD görüntüsü yüklenirken kullanılan salt okunur modu alır veya ayarlar"
type: docs
weight: 80
url: /tr/net/aspose.psd.imageloadoptions/psdloadoptions/readonlytype/
---
{{< psd/tize >}}
## PsdLoadOptions.ReadOnlyType property

PSD görüntüsü yüklenirken kullanılan salt okunur modu alır veya ayarlar.

```csharp
public ReadOnlyMode ReadOnlyType { get; set; }
```

### Property Value

Aşağıdakilerden biri: [`ReadOnlyMode`](../readonlymode/)

* !:ReadOnlyMode.None – No restrictions. Image content can be modified.
* !:ReadOnlyMode.Default – The image is fully read-only.
* !:ReadOnlyMode.MetadataEdit – Only metadata can be edited (such as [`ImageResources`](../../../aspose.psd.fileformats.psd/psdimage/imageresources/)), while image pixel content remains read-only.

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

* enum [ReadOnlyMode](../../readonlymode/)
* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


